URL = https://canary.discordapp.com/api/users/@me/feed/settings

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* subscribed_games
    * array
* subscribed_users
    * array
* unsubscribed_users
    * array
* unsubscribed_games
    * array

## Unauthorized Return
* code
    * int
* message
    * string