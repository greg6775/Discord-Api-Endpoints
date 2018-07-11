URL = https://canary.discordapp.com/api/users/:user-id/relationships

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* username
    * string
* disriminator
    * string
* id
    * string
* avatar
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