## API ENDPOINTS

URL: https://canary.discordapp.com/api/v6

# GET

### /applications
### /applications/detectable
### /applications/:application-id/branches

### /application-news
### /application-news/:application-news-id

### /activities

### /auth/login
### /auth/register
### /auth/consent-required

### /channels/:channel-id
### /channels/:channel-id/call
### /channels/:channel-id/follower-stats
### /channels/:channel-id/follower-message-stats
### /channels/:channel-id/invites
### /channels/:channel-id/messages
### /channels/:channel-id/messages/search
### /channels/:channel-id/messages/:message-id
### /channels/:channel-id/messages/:message-id:/reactions/:emoji
### /channels/:channel-id/pins
### /channels/:channel-id/store-listing
### /channels/:channel-id/store-listing/:sku-id
### /channels/:channel-id/webhooks

### /connections/:provider-id/authorize

### /experiments

### /friend-suggestions

### /games

### /gateway
### /gateway/bot

### /guilds/:guild-id
### /guilds/:guild-id/analytics/overview
### /guilds/:guild-id/applications
### /guilds/:guild-id/audit-logs
### /guilds/:guild-id/bans
### /guilds/:guild-id/channels
### /guilds/:guild-id/embed
### /guilds/:guild-id/emojis
### /guilds/:guild-id/emojis/:emoji-id
### /guilds/:guild-id/integrations
### /guilds/:guild-id/invites
### /guilds/:guild-id/members
### /guilds/:guild-id/members/:user-id
### /guilds/:guild-id/messages/search
### /guilds/:guild-id/premium/subscriptions
### /guilds/:guild-id/prune
### /guilds/:guild-id/regions
### /guilds/:guild-id/roles
### /guilds/:guild-id/vanity-url
### /guilds/:guild-id/webhooks

### /invites/:invite-code
### /invite/:invite-code

### /oauth2/applications
### /oauth2/applications/:application-id
### /oauth2/applications/:application-id/rpc
### /oauth2/applications/:application-id/assets
### /oauth2/authorize?client_id=:client-id
### /oauth2/authorize/webhook-channels?guild_id=:guild-id
### /oauth2/tokens
### /oauth2/tokens/:application-id

### /tutorial

### /users/:user-id
### /users/:user-id/channels
### /users/:user-id/profile
### /users/:user-id/relationships
### /users/:user-id/sessions/:session-id/activities/:application-id/metadata
### /users/@me
### /users/@me?with_analytics_token=true
### /users/@me/activities/statistics/applications
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
### /users/@me/relationships
### /users/@me/settings

### /voice/regions
### /voice/ice

### /webhooks/:webhook-id
### /webhooks/:webhook-id/:webhook-token

# POST

### /channels/:channel-id/messages
### /channels/:channel-id/messages/bulk-delete
### /channels/:channel-id/invites
### /channels/:channel-id/typing

### /guilds/:guild-id/emojis
### /guilds/:guild-id/channels
### /guilds/:guild-id/roles
### /guilds/:guild-id/prune
### /guilds/:guild-id/integrations
### /guilds/:guild-id/integrations/:integration-id/sync