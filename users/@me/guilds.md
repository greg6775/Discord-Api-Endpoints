URL = https://canary.discordapp.com/api/users/@me/guilds

## Header
* Authorization
    * User-Token (without ")
## RETURNS

# OK Return
* owner
    * boolean
* permissions
    * int
* icon
    * string
* id
    * string
* name
    * string

# Unauthorized Return
* code
    * int
* message
    * string