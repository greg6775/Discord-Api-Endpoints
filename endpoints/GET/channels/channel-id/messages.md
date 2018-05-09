URL = https://canary.discordapp.com/api/channels/:channel-id/messages

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* attachments
    * array
* tts
    * boolean
* embeds
    * array
* timestamp
    * string
* mention_everyone
    * boolean
* id
    * string
* pinned
    * boolean
* edited_timestamp
    * boolean/string
* author
    * array
        * username
            * string
        * discriminator
            * string
        * id
            * string
        * avatar
            * string
* mention_roles
    * array
* content
    * string
* channel_id
    * string
* mentions
    * array
        * username
            * string
        * discriminator
            * string
        * bot
            * boolean
        * id
            * string
        * avatar
            * string
* type
    * int

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