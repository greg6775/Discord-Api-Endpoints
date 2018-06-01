URL = https://canary.discordapp.com/api/channels/:channel-id/invites

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* max_age
    * int
* code
    * string
* guild
    * array
        * verification_level
            * int
        * features
            * array
        * name
            * string
        * splash
            * boolean
        * id
            * string
        * icon
            * boolean/string
* created_at
    * string
* temporary
    * boolean
* uses
    * int
* max_uses
    * int
* inviter
    * array
        * username
            * string
        * discriminator
            * string
        * id
            * string
        * avatar
            * boolean/string
* channel
    * type
        * int
    * id
        * string
    * name
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

## Missing Permissions Return
* code
    * int
* message
    * string