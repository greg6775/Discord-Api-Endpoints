URL = https://canary.discordapp.com/api/channels/:channel-id

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* guild_id
    * string
* name
    * string
* permission_overwrites
    * array
        * deny
            * int
        * type
            * string
        * id
            * string
        * allow
            * int
* topic
    * boolean/string
* parent_id
    * boolean/string
* nsfw
    * boolean
* position
    * int
* last_message_id
    * string
* type
    * int
* id
    * string

## Unknown Channel Return
* code
    * int
* message
    * string

## Unauthorized Return
* code
    * int
* message
    * string