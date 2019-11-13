## API ENDPOINTS

URL: https://canary.discordapp.com/api/v6

# GET

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

### /channels/:channel-id
### /channels/:channel-id/messages
### /channels/:channel-id/messages/:message-id
### /channels/:channel-id/messages/:message-id:/reactions/:emoji
### /channels/:channel-id/invites
### /channels/:channel-id/pins
### /channels/:channel-id/webhooks
### /channels/:channel-id/call

### /guilds/:guild-id
### /guilds/:guild-id/audit-logs
### /guilds/:guild-id/webhooks
### /guilds/:guild-id/emojis
### /guilds/:guild-id/emojis/:emoji-id
### /guilds/:guild-id/channels
### /guilds/:guild-id/members
### /guilds/:guild.id/members/:user-id
### /guilds/:guild-id/bans
### /guilds/:guild-id/roles
### /guilds/:guild-id/prune
### /guilds/:guild-id/regions
### /guilds/:guild-id/invites
### /guilds/:guild-id/integrations
### /guilds/:guild-id/embed
### /guilds/:guild-id/vanity-url

### /invites/:invite-code
### /invite/:invite-code

### /voice/regions
### /voice/ice

### /webhooks/:webhook-id
### /webhooks/:webhook-id/:webhook-token

### /activities

### /games

### /friend-suggestions

### /tutorial

### /experiments

### /auth/login
### /auth/register

### /gateway
### /gateway/bot

### /applications

### /oauth2/applications
### /oauth2/applications/:application-id
### /oauth2/applications/:application-id/rpc
### /oauth2/applications/:application-id/assets
### /oauth2/tokens

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