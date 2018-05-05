URL = https://canary.discordapp.com/api/users/@me/activities/statistics/applications

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* last_played_at
    * string
* application_id
    * string
* total_duration
    * int

## Unauthorized Return
* code
    * int
* message
    * string