URL = https://canary.discordapp.com/api/users/@me/relationships

## Header
* Authorization
    * User-Token (without ")
### RETURNS

# OK Return
* type
    * boolean
* id
    * string
* user
    * username
        * string
    * discriminator
        * string
    * id
        * string
    * avatar
        * string

# Unauthorized Return
* code
    * int
* message
    * string