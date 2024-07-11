---
label: What are Crimes?
order: 750
icon: checklist
author:
  - name: BxBY
    avatar: ./img/bxby.jpg
  - name: Tom
    avatar: ./img/Tom.png
---
Certainly!

---

**Understanding "Crimes" in RexZ Discord Bot**

In RexZ Discord bot, the term "crimes" takes on a unique meaning—it's tied to Audit Log Events. This means that actions performed by users within the server, which generate audit log events, are categorized as "crimes" within the bot's framework.

For instance, actions like kicking or banning members, creating or deleting channels, and role updates can all be interpreted as "crimes" within RexZ. Moreover, if a user who isn't whitelisted triggers any of these events, it could be logged as a "crime" by the bot.

This approach, drawing from Discord.js documentation, provides a structured means of monitoring and managing server activity. By defining "crimes" based on audit log events, RexZ enhances moderation capabilities and fosters accountability within the server. It allows administrators to keep track of significant user actions, aiding in maintaining a healthy and respectful community environment.

---

Audit Log Events   | Crime Values {.compact}
---    | ---
BotAdd | 28
ChannelCreate | 10
ChannelDelete | 12
ChannelUpdate | 11
EmojiCreate | 60
EmojiDelete | 62
EmojiUpdate | 61
GuildUpdate | 1
MemberBanAdd | 22
MemberBanRemove | 23
MemberDisconnect | 27
MemberKick | 20
MemberMove | 26
MemberPrune | 21
MemberRoleUpdate | 25
MemberUpdate | 24
MessageBulkDelete | 73
MessageDelete | 72
RoleCreate | 30
RoleDelete | 32
RoleUpdate | 31
StickerCreate | 90
StickerDelete | 92
StickerUpdate | 91
ThreadCreate | 110
ThreadDelete | 112
ThreadUpdate | 111
WebhookCreate | 50
WebhookDelete | 52
WebhookUpdate | 51

Didn't found crime value? Don't worry [:link: Read more about "Audit Log Events" and their "Crime" values](https://discord-api-types.dev/api/discord-api-types-v10/enum/AuditLogEvent)