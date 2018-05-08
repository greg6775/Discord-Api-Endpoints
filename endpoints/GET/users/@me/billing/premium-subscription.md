URL = https://canary.discordapp.com/api/users/@me/billing/premium-subscription

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* status
    * int
* ended_at
    * string
* canceled_at
    * string
* created_at
    * string
* current_period_end
    * string
* current_period_start
    * string
* plan
    * string

## No Nitro Return
* code
    * int
* message
    * string

## Unauthorized Return
* code
    * int
* message
    * string