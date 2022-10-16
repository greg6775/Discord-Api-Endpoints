# Discord-Api-Endpoints

A list of useful Discord API endpoints

If you find any mistakes please create a Pull request.

## `X-Super-Properties` Header

Discord now requires the `X-Super-Properties` HTTP header for some endpoints.
Those endpoints are marked with an asterisk (*).

This header may be a new deterrent against bots. However, it does not provide
personally-identifiable information. If you send a request to an endpoint, which
requires the new header, it will return the following:

```json
{
  "message": "Missing Access",
  "code": 50001
}
```

The new header is a Base64 string, which decodes to:

```json
{
  "os": "Windows",
  "browser": "Discord Client",
  "release_channel": "canary",
  "client_version": "1.0.49",
  "os_version": "10.0.22621",
  "os_arch": "x64",
  "system_locale": "en-US",
  "client_build_number": "152450",
  "client_event_source": null
}
```

However, Discord only requires the following information in order to process the
request:

```json
{
  "os": "Windows",
  "client_build_number": 152450
}
```

This encodes to

```
ewogICJvcyI6ICJXaW5kb3dzIiwKICAiY2xpZW50X2J1aWxkX251bWJlciI6IDE1MjQ1MAp9
```
