## API ENDPOINTS

URL: https://canary.discordapp.com/api/v6

# GET

## /users/:user-id
## /users/:user-id/profile
## /users/@me
## /users/@me/connections
## /users/@me/guilds
## /users/@me/channels
## /users/@me/relationships
## /users/@me/activities/statistics/applications
## /users/@me/settings
## /users/@me/mentions
## /users/@me/feed/settings
## /users/@me/billing
## /users/@me/billing/premium-subscription
## /users/@me/billing/payments

## /channels/:channel-id
## /channels/:channel-id/messages
## /channels/:channel-id/messages/:message-id
## /channels/:channel-id/messages/:message-id:/reactions/:emoji
## /channels/:channel-id/invites
## /channels/:channel-id/pins
## /channels/:channel-id/webhooks
## /channels/:channel-id/call

## /guilds/:guild-id
## /guilds/:guild-id/audit-logs
## /guilds/:guild-id/webhooks
## /guilds/:guild-id/emojis
## /guilds/:guild-id/emojis/:emoji-id
## /guilds/:guild-id/channels
## /guilds/:guild-id/members
## /guilds/:guild.id/members/:user-id
## /guilds/:guild-id/bans
## /guilds/:guild-id/roles
## /guilds/:guild-id/prune
## /guilds/:guild-id/regions
## /guilds/:guild-id/invites
## /guilds/:guild-id/integrations
## /guilds/:guild-id/embed
## /guilds/:guild-id/vanity-url

## /invites/:invite-code

## /voice/regions
## /voice/ice

## /webhooks/:webhook-id
## /webhooks/:webhook-id/:webhook-token

## /activities

## /games

## /friend-suggestions

## /tutorial

## /experiments

## /auth/login
## /auth/register

## /gateway
## /gateway/bot

## /applications

## /oauth2/applications/:game-id/rpc
## /oauth2/applications/:game-id/assets
## /oauth2/tokens

# POST

## /channels/:channel-id/messages
## /channels/:channel-id/messages/bulk-delete
## /channels/:channel-id/invites
## /channels/:channel-id/typing

## /guilds/:guild-id/emojis
## /guilds/:guild-id/channels
## /guilds/:guild-id/roles
## /guilds/:guild-id/prune
## /guilds/:guild-id/integrations
## /guilds/:guild-id/integrations/:integration-id/sync