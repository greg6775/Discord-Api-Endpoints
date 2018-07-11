URL = https://canary.discordapp.com/api/users/:user-id/profile

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* premium_since
    * boolean/string
* mutual_guilds
    * array
        * nick
            * boolean/string
        * id
            * string
* user
    * username
        * string
    * discriminator
        * string
    * flags
        * int
    * id
        * string
    * avatar
        * boolean/string
* connected_accounts
    * array
        * verified
            * boolean
        * type
            * string
        * id
            * string
        * name
            * string

## Unknown User Return
* code
    * int
* message
    * string

## Missing Acces Return
* code
    * int
* message
    * string

## Unauthorized Return
* code
    * int
* message
    * string