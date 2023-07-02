# docs-v2
test

# Client endpoints
```
/ # Redirects to /app
/app
/@me
/@me/MEMBER_ID # This is DM (Direct Message)
/guild/GUILD_ID
/guild/GUILD_ID/settings
/guild/GUILD_ID/channel/CHANNEL_ID
/invite/INVITE_CODE
```

# API endpoints
```
GET /api/users/@me (returns user, and available DMs & Guilds)
GET /api/guild/GUILD_ID (returns guild settings, roles)
GET /api/guild/GUILD_ID/channel/CHANNEL_ID (returns channel info)
GET /api/guild/GUILD_ID/channel/CHANNEL_ID/send (send message to channel)
GET /api/guild/GUILD_ID/channel/CHANNEL_ID/messages (returns messages)
GET /api/guild/GUILD_ID/channel/CHANNEL_ID/members (returns members in channel)
```
