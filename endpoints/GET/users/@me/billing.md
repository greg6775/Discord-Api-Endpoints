URL = https://canary.discordapp.com/api/users/@me/billing

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* premium_subscription
    * status
        * int
    * ended_at
        * string/boolean
    * canceled_at
        * string/boolean
    * created_at
        * string
    * current_period_end
        * string
    * current_period_start
        * string
    * plan
        * string
* payment_source
    * type
        * string
    * email
        * string
* payment_gateway
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