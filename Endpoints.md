## API ENDPOINTS
&nbsp;
&nbsp;
Base-URL: https://canary.discord.com/api/v9
&nbsp;
# GET
&nbsp;
### /applications
### /applications/:application-id
### /applications/:application-id/branches
### /applications/:application-id/branches/:branch-id/builds
### /applications/:application-id/branches/:branch-id/builds/:build-id
### /applications/:application-id/branches/:branch-id/builds/live?locale=:locale&platform=:platform
### /applications/:application-id/commands
### /applications/:application-id/commands/:command-id
### /applications/:application-id/guilds/:guild-id/commands
### /applications/:application-id/guilds/:guild-id/commands/:command-id
### /applications/:application-id/guilds/:guild-id/commands/:command-id/permissions
### /applications/:application-id/guilds/:guild-id/commands/permissions
### /applications/:application-id/skus
### /applications/:application-id/public
### /applications/detectable
&nbsp;
### /application-news
### /application-news/:application-news-id
&nbsp;
### /activities
### /activities/statistics/applications/:application-id
&nbsp;
### /auth/location-metadata
### /auth/login
### /auth/register
&nbsp;
### /channels/:channel-id
### /channels/:channel-id/call
### /channels/:channel-id/follower-stats
### /channels/:channel-id/follower-message-stats
### /channels/:channel-id/invites
### /channels/:channel-id/messages
### /channels/:channel-id/messages/search
### /channels/:channel-id/messages/:message-id
### /channels/:channel-id/messages/:message-id/reactions/:emoji
### /channels/:channel-id/pins
### /channels/:channel-id/store-listing
### /channels/:channel-id/store-listing/:sku-id
### /channels/:channel-id/users/@me/threads/archived/private
### /channels/:channel-id/webhooks
### /channels/:channel-id/threads/active
### /channels/:channel-id/threads/archived/public
### /channels/:channel-id/threads/archived/private
&nbsp;
### /connections/:provider-id/authorize
&nbsp;
### /discoverable-guilds
&nbsp;
### /discovery/categories
&nbsp;
### /entitlements/gift-codes/:gift-code
&nbsp;
### /experiments
### /experiments?with_guild_experiments=true
&nbsp;
### /friend-suggestions
&nbsp;
### /gateway
### /gateway/bot
&nbsp;
### /gifs/suggest?q=:query
### /gifs/trending
&nbsp;
### /guilds/:guild-id
### /guilds/:guild-id/analytics/overview
### /guilds/:guild-id/analytics/engagement/overview
### /guilds/:guild-id/analytics/growth-activation/overview
### /guilds/:guild-id/analytics/growth-activation/retention
### /guilds/:guild-id/applications
### /guilds/:guild-id/audit-logs
### /guilds/:guild-id/bans
### /guilds/:guild-id/bans/:user-id
### /guilds/:guild-id/channels
### /guilds/:guild-id/discovery-metadata
### /guilds/:guild-id/discovery-requirements
### /guilds/:guild-id/emojis
### /guilds/:guild-id/emojis/:emoji-id
### /guilds/:guild-id/integrations
### /guilds/:guild-id/invites
### /guilds/:guild-id/members
### /guilds/:guild-id/members/:user-id
### /guilds/:guild-id/member-verification
### /guilds/:guild-id/messages/search
### /guilds/:guild-id/premium/subscriptions
### /guilds/:guild-id/preview
### /guilds/:guild-id/prune
### /guilds/:guild-id/regions
### /guilds/:guild-id/roles
### /guilds/:guild-id/templates
### /guilds/:guild-id/vanity-url
### /guilds/:guild-id/webhooks
### /guilds/:guild-id/welcome-screen
### /guilds/:guild-id/widget
### /guilds/:guild-id/widget.json
### /guilds/:guild-id/widget.png
### /guilds/templates/:template-code
&nbsp;
### /invites/:invite-code
### /invite/:invite-code
&nbsp;
### /oauth2/@me
### /oauth2/applications
### /oauth2/applications/:application-id
### /oauth2/applications/:application-id/rpc
### /oauth2/applications/:application-id/assets
### /oauth2/authorize?client_id=:client-id
### /oauth2/authorize/webhook-channels?guild_id=:guild-id
### /oauth2/tokens
### /oauth2/tokens/:token
&nbsp;
### /partners/:guild-id/requirements
### /partners/connections/
&nbsp;
### /store/published-listings/applications/:application-id
### /store/published-listings/skus/:application-id
### /store/skus/:application-id
### /store/skus/:application-id/listings
&nbsp;
### /streams/:stream-key/preview
&nbsp;
### /teams
&nbsp;
### /users/:user-id
### /users/:user-id/channels
### /users/:user-id/profile
### /users/:user-id/relationships
### /users/:user-id/sessions/:session-id/activities/:application-id/metadata
### /users/@me
### /users/@me?with_analytics_token=true
### /users/@me/activities/statistics/applications
### /users/@me/affinities/guilds
### /users/@me/affinities/users
### /users/@me/applications/:application-id/achievements
### /users/@me/applications/:application-id/entitlements
### /users/@me/billing/payments
### /users/@me/billing/payment-sources
### /users/@me/billing/payment-sources/:payment-source
### /users/@me/billing/stripe/payment-intents/payments/:payment
### /users/@me/billing/subscriptions
### /users/@me/billing/subscriptions/:subscription-id
### /users/@me/billing/trials/:trial-id/eligibility
### /users/@me/channels
### /users/@me/connections
### /users/@me/consent
### /users/@me/entitlements/gifts
### /users/@me/feed/settings
### /users/@me/feed/unsubscribed_users
### /users/@me/guilds
### /users/@me/guilds/premium/subscriptions
### /users/@me/guilds/premium/subscription-slots
### /users/@me/guilds/premium/subscriptions/cooldown
### /users/@me/harvest
### /users/@me/library
### /users/@me/mentions
### /users/@me/notes
### /users/@me/notes/:note-user-id
### /users/@me/relationships
### /users/@me/settings
&nbsp;
### /voice/regions
### /voice/ice
&nbsp;
### /webhooks/:application-id/:interaction-token/messages/@original
### /webhooks/:webhook-id
### /webhooks/:webhook-id/:webhook-token
&nbsp;
&nbsp;
# POST (Not finished)
&nbsp;
### /channels/:channel-id/messages
### /channels/:channel-id/messages/bulk-delete
### /channels/:channel-id/invites
### /channels/:channel-id/typing
&nbsp;
### /guilds/:guild-id/emojis
### /guilds/:guild-id/channels
### /guilds/:guild-id/roles
### /guilds/:guild-id/prune
### /guilds/:guild-id/integrations
### /guilds/:guild-id/integrations/:integration-id/sync
