URL = https://canary.discordapp.com/api/users/@me/mentions

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* attachments
    * array
* tts
    * boolean
* embeds
    * description
        * string
    * title
        * string
    * url
        * string
    * provider
        * url
            * string/boolean
        * name
            string/boolean
    * type
        * string
    * thumbnail
        * url
            * string
        * width
            * int
        * proxy_url
            * string
        * height
            * int
* timestamp
    * string
* mention_everyone
    * string
* id
    * string
* pinned
    * boolean
* edited_timestamp
    * string or boolean
* author
    * username
        * string
    * discriminator
        * string
    * id
        * string
    * avatar
        * string
* mention_roles
    * array
* content
    * string
* channel_id
    * string
* mentions
    * array
* type
    * int

## Unauthorized Return
* code
    * int
* message
    * string