---
label: Anti Nuke # Label - shows at navigation tab
order: 100 # Page order in folder
icon: shield # Page icon - shows at navigation tab
author: # Who written this page
  - name: BxBY # Author name
    avatar: ../../img/bxby.jpg # Author avatar
  - name: Tom
    avatar: ../../img/Tom.png
meta: # Meta tag - works like <meta>
  title: "Anti Nuke" # Page title (this will override default meta.title set in config)
description: "Protect your Discord server from malicious actions with RexZ’s Anti-Nuke feature. Automatically detect and prevent server raids, nukes, and unauthorized actions to keep your community secure." # Page description
category: [setup, config, commands] # Page category (might be multiple categories - [category1, category2])
tags: [antinuke, commands] # Tags to find page easily with search
route: "/antinuke/" # Change default route set by retype
---

# Anti Nuke
RexZ provides a powerful and reliable Anti-Nuke system to ensure the safety and security of your Discord server. This feature is designed to prevent malicious activities and unauthorized changes that could harm your community.
# What is Anti-Nuke?
Anti-Nuke refers to a set of protective measures designed to safeguard a Discord server against malicious actions such as mass bans, channel deletions, or unauthorized role modifications, commonly known as "nuking."
## Why Choose RexZ for Anti-Nuke?
- **Real-Time Monitoring:** RexZ continuously monitors server activity and instantly responds to threats.
- **Customizable Settings:** Tailor the Anti-Nuke system to your server's unique needs.
- **User-Friendly Commands:** Effortlessly manage the Anti-Nuke feature using simple and intuitive commands.

---
## Anti Nuke Features in RexZ
- Antiban
- Antibot
- Anti channel create
- Anti channel delete
- Anti channel update
- Anti community
- Anti Emoji create
- Anti Emoji delete
- Anti Emoji Update
- Anti Everyone
- Anti GuildUpdate
- Anti Kick
- Anti Member Update
- Anti Public Role
- Anti Role Create
- Anti Role Delete
- Anti Role Update
- Anti Self Bot
- Anti Unverified Bot
- Anti Webhook
---

## Anti ban
### What is AntiBan?
Sets limit on how many bans bot will get triggered and take action on the user who used ban.
For example on [**-antiban 1**] bot will get triggered on 1 ban by anyone and bot will take action against that user.

{.compact}
Aliases   | Usage
---       | ---
antib     | antiban <1/2/3/4/...>
### Example
--![Antiban limit](../../img/Commands/AutoMod/antiban.png)--
--![Antiban off](../../img/Commands/AutoMod/antibanoff.png)--

---

## Anti Bot
### What is AntiBot?
Enabling antibot will restricts user from adding bots in guild.

### Example
--![Antibot on](../../img/Commands/AutoMod/antiboton.png)--
--![Antibot off](../../img/Commands/AutoMod/antibotoff.png)--

---

## Anti Channel Create

### What is AntiChannelCreate?
Set guild's channel create limit. For example [**-antichannelc 2**] bot will be triggered when the user tries to create second channel in guild.

{.compact}
Aliases   | Usage
---       | ---
anticc     | antichannelc <1/2/3/4/...>

### Example
--![antichannel create limit](../../img/Commands/AutoMod/antichannelc.png)--
--![antichannel create off](../../img/Commands/AutoMod/antichannelcoff.png)--

---
## Anti channel delete
### What is AntiChannelDelete?
Set guild's channel delete limit. For example [**-antichanneld 3**] bot will be triggered when the user tries to delete third channel in guild.

{.compact}
Aliases   | Usage
---       | ---
anticd     | antichanneld <1/2/3/4/...>

### Example
--![antichannel delete limit](../../img/Commands/AutoMod/antichanneld.png)--
--![antichannel delete off](../../img/Commands/AutoMod/antichanneldoff.png)--

---
## Anti channel update
### What is AntiChannelUpdate?
Enabling anti channel update will restrict users to update any channel in guild.

{.compact}
Aliases   | Usage
---       | ---
anticu     | antichannelu <1/2/3/4/...>

### Example
--![antichannel update limit](../../img/Commands/AutoMod/antichannelu.png)--
--![antichannel update off](../../img/Commands/AutoMod/antichanneluoff.png)--

---
## Anti community
### What is AntiCommunity?
anti community restrict users from enabling or disabling community in guild .

{.compact}
Aliases   | Usage
---       | ---
anticom     | anticommunity <on/off>

### Example
--![anticommunity on](../../img/Commands/AutoMod/antic.png)--
--![anticommunity off](../../img/Commands/AutoMod/anticoff.png)--

---

## Anti emoji create

### What is AntiEmojiCreate?
Enabling anti emoji restricts user from adding emoji in guild.

{.compact}
Aliases   | Usage
---       | ---
antiec     | antiemojicreate <1/2/3/4/...>


### Example
--![antiemoji create limit](../../img/Commands/AutoMod/antiemojicon.png)--
--![antiemoji create off](../../img/Commands/AutoMod/antiemojicoff.png)--

---

## Anti emoji delete

### What is AntiEmojiDelete?
Enabling anti emoji restricts user from deleting emoji in guild.

{.compact}
Aliases   | Usage
---       | ---
antied     | antiemojidelete <1/2/3/4/...>


### Example
--![antiemoji delete limit](../../img/Commands/AutoMod/antiemojidon.png)--
--![antiemoji delete off](../../img/Commands/AutoMod/antiemojidoff.png)--

---

## Anti emoji update
### What is AntiEmojiUpdate?
Enabling anti emoji update restricts user from updating emoji name in guild.

{.compact}
Aliases   | Usage
---       | ---
antieu     | antiemojiupdate <1/2/3/4/...>


### Example
--![antiemoji update limit](../../img/Commands/AutoMod/antiemojiupon.png)--
--![antiemoji update off](../../img/Commands/AutoMod/antiemojiupoff.png)--

---

## Anti everyone
### What is AntiEveryone?
Enablung anti everyone restricts user from using **@everyone** tag in guild.
### Example
--![antieveryone on](../../img/Commands/AutoMod/antieveryoneon.png)--
--![antieveryone off](../../img/Commands/AutoMod/antieveryoneoff.png)--
---
## Anti guild update
### What is AntiGuildUpdate?
Enabling anti guild update restricts user from updating the guild.

{.compact}
Aliases   | Usage
---       | ---
antigu     | antiguildupdate <1/2/3/4/...>

### Example
--![antiguild update limit](../../img/Commands/AutoMod/antiguon.png)--
--![antiguild update off](../../img/Commands/AutoMod/antiguoff.png)--

---

## Anti kick
### What is AntiKick?
Sets limit on how many kicks bot will get triggered and take action on the user who used kick.
For example on [**-antikick 1**] bot will get triggered on 1 kick by anyone and bot will take action against that user.

{.compact}
Aliases   | Usage
---       | ---
antik    | antikick <1/2/3/4/...>

### Example
--![antikick limit](../../img/Commands/AutoMod/antikick.png)--
--![antikick off](../../img/Commands/AutoMod/antikickoff.png)--

---

## Anti member update
### What is AntiMemberUpdate?
Enabling anti member update restricts user from updating their/others role with dangerous permission in guild.

{.compact}
Aliases   | Usage
---       | ---
antimu    | antimemberupdate <1/2/3/4/...>

### Example
--![antimember update limit](../../img/Commands/AutoMod/antimemberuon.png)--
--![antimember update off](../../img/Commands/AutoMod/antimemberupdateoff.png)--

---
## Anti public role
### What is AntiPublicRole?
Adding role in antipublic role list will restrict users from tagging that role in guild. for example [**@faimly**] role if added then users trying to tag that role will trigger the bot.

{.compact}
Aliases   | Usage
---       | ---
antipr add/remove    | antipublicrole <add/remove> @role

### Example
--![antipublic role add](../../img/Commands/AutoMod/antipublicadd.png)--
--![antipublic role remove](../../img/Commands/AutoMod/antipublicoff.png)--
--![antipublic role list](../../img/Commands/AutoMod/antipublic.png)--
---
## Anti role create
### What is AntiRoleCreate?
Sets limit on how many role creations will trigger the bot. For example [**-antirolec 2**] bot will get triggered when someone creates second role in guild and bot will take action against that user.

{.compact}
Aliases   | Usage
---       | ---
antirc    | antirolecreate <1/2/3/4/...>

### Example
--![antirole create limit](../../img/Commands/AutoMod/antirolecon.png)--
--![antirole create off](../../img/Commands/AutoMod/antirolecofff.png)--

---

## Anti role delete
### What is AntiRoleDelete?
sets limit on how many role deletions will trigger the bot. For example [**-antiroled 2**] bot will get triggered when someone deletes second role in guild and bot will take action against that user.

{.compact}
Aliases   | Usage
---       | ---
antird    | antiroledelete <1/2/3/4/...>

### Example
--![antirole delete limit](../../img/Commands/AutoMod/antiroledon.png)--
--![antirole delete off](../../img/Commands/AutoMod/antiroledofff.png)--

---

## Anti role update
### What is AntiRoleUpdate?
Enabling this restrict users from updating role permissions in guild.

{.compact}
Aliases   | Usage
---       | ---
antiru    | antiroleupdate <1/2/3/4/...>

### Example
--![antirole update limit](../../img/Commands/AutoMod/antiruon.png)--
--![antirole update off](../../img/Commands/AutoMod/antiroleuofff.png)--

---

## Anti self-bot
### What is AntiSelfBot?
Enabling this will restrict users from selfbotting in guild.
### Example
--![antiselfbot on](../../img/Commands/AutoMod/antiselfboton.png)--
--![antiselfbot off](../../img/Commands/AutoMod/antiselfbotoff.png)--
---
## Anti unverified bot
### What is AntiUnverifiedBot?
Enabling this will restrict users from adding unverified bots in guild.
### Example
--![antiunverifiedbot on](../../img/Commands/AutoMod/antiunverion.png)--
--![antiunverifiedbot off](../../img/Commands/AutoMod/antiunverioff.png)--
---
## Anti webhook
### What is AntiWebhook?
Enabling this will restrict users from creating webhooks in guild.

### Example
--![antiwebhook limit](../../img/Commands/AutoMod/antiwebhookon.png)--
--![antiwebhook off](../../img/Commands/AutoMod/antiwebhookoff.png)--