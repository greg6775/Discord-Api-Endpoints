URL = https://canary.discordapp.com/api/users/@me/billing/payments

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* status
    * int
* currency
    * string
* canceled_at
    * string
* amount
    * int
* description
    * string
* amount_refunded
    * int
* created_at
    * string
* id
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