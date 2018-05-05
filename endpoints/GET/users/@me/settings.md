URL = https://canary.discordapp.com/api/users/@me/settings

## Header
* Authorization
    * User-Token (without ")
# RETURNS

## OK Return
* render_reactions
    * boolean
* afk_timeout
    * int
* locale
    * string
* inline_embed_media
    * boolean
* gif_auto_play
    * boolean
* explicit_content_filter
    * int
* message_display_compact
    * boolean
* theme
    * string
* render_embeds
    * boolean
* show_current_game
    * boolean
* inline_attachment_media
    * boolean
* status
    * string
* timezone_offset
    * int
* enable_tts_command
    * boolean
* restricted_guilds
    * array
* detect_platform_accounts
    * boolean
* developer_mode
    * boolean
* default_guilds_restricted
    * boolean
* convert_emoticons
    * boolean
* guild_positions
    * array
* friend_source_flags
    * mutual_friends
        * boolean
* animate_emoji
    * boolean

## Unauthorized Return
* code
    * int
* message
    * string