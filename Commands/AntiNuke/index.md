---
icon: shield
label: Anti Nuke
order: 100
author:
  - name: BxBY
    avatar: ../../img/bxby.jpg
  - name: Tom
    avatar: ../../img/Tom.png
tags: [antinuke]
---

# Anti ban
### Description
Sets limit on how many bans bot will get triggered and take action on the user who used ban.
For example on [**-antiban 1**] bot will get triggered on 1 ban by anyone and bot will take action against that user.

{.compact}
Aliases   | Usage
---       | ---
antib  | -antiban <1/2/3/4/...>

### Usage
!!!primary Set guild's antiban limit
`-antiban <1/2/3/4/...>`
--![Antiban limit](../../img/Commands/AutoMod/antiban.png)--
!!!

!!!primary Disable antiban
`-antiban off`
--![Antiban off](../../img/Commands/AutoMod/antibanoff.png)--
!!!

### Alias
!!!info
`-antib`
--![Antiban Alias](../../img/Commands/AutoMod/antib.png)--
!!!

# Anti bot
### Description
Enabling antibot will restricts user from adding bots in guild.

### Usage
!!!primary
`-antibot <on/off>`
--![Antibot on](../../img/Commands/AutoMod/antiboton.png)--
--![Antibot off](../../img/Commands/AutoMod/antibotoff.png)--
!!!

# Anti channel create
### Description
Set guild's channel create limit. For example [**-antichannelc 2**] bot will be triggered when the user tries to create second channel in guild

### Usage
!!!primary Set limit
`-antichannelc <1/2/3/4/...>`
--![antichannel create value](../../img/Commands/AutoMod/antichannelc.png)--
!!!

!!!primary Disable
`-antichannelc off`
--![antichannel create off](../../img/Commands/AutoMod/antichannelcoff.png)--
!!!

# Anti channel delete
### Description
Set guild's channel delete limit. For example [**-antichanneld 3**] bot will be triggered when the user tries to delete third channel in guild

### Usage
!!!primary Set limit
`-antichanneld <1/2/3/4/...>`
--![antichannel delete value](../../img/Commands/AutoMod/antichanneld.png)--
!!!

!!!primary Disable
`-antichanneld off`
--![antichannel delete off](../../img/Commands/AutoMod/antichanneldoff.png)--
!!!

# Anti channel update
### Description
Enabling anti channel update will restrict users to update any channel in guild.

### Usage
!!!primary
`-antichannelu <on/off>`
--![antichannel update on](../../img/Commands/AutoMod/antichannelu.png)--
--![antichannel update off](../../img/Commands/AutoMod/antichanneluoff.png)--
!!!

# Anti community
### Description
anti community restrict users from enabling or disabling community in guild .

### Usage
!!!primary
`-anticommunity <on/off>`
--![anticommunity on](../../img/Commands/AutoMod/antic.png)
--![anticommunity off](../../img/Commands/AutoMod/anticoff.png)
!!!

# Anti emoji
### Description
Enabling anti emoji restricts user from adding or removing emoji in guild.

### Usage
!!!primary
`-antiemoji <on/off>`
--![antiemoji on](../../img/Commands/AutoMod/antiemojion.png)--
--![antiemoji off](../../img/Commands/AutoMod/antiemojioff.png)--
!!!

# Anti emoji update
### Description
Enabling anti emoji update restricts user from updating emoji name in guild.

### Usage
!!!primary
`-antiemojiu <on/off>`
--![antiemoji update on](../../img/Commands/AutoMod/antiemojiuon.png)--
--![antiemoji update off](../../img/Commands/AutoMod/antiemojiuoff.png)--
!!!

# Anti everyone
### Description
Enablung anti everyone restricts user from using **@everyone** tag in guild.

### Usage
!!!primary
`-antieveryone <on/off>`
--![antieveryone on](../../img/Commands/AutoMod/antieveryoneon.png)--
--![antieveryone off](../../img/Commands/AutoMod/antieveryoneoff.png)--
!!!

# Anti guild update
### Description
Enabling anti guild update restricts user from updating the guild.

### Usage
!!!primary
`-antiguildu <on/off>`
--![antiguild update on](../../img/Commands/AutoMod/antiguilduon.png)--
--![antiguild update off](../../img/Commands/AutoMod/antiguilduoff.png)--
!!!

# Anti kick
### Description
Sets limit on how many kicks bot will get triggered and take action on the user who used kick.
For example on [**-antikick 1**] bot will get triggered on 1 kick by anyone and bot will take action against that user.

### Usage
!!!primary Set limit
`-antikick <1/2/3/4/...>`
--![antikick limit](../../img/Commands/AutoMod/antiban.png)--
!!!

!!!primary Disable
`-antikick off`
--![antikick off](../../img/Commands/AutoMod/antibanoff.png)--
!!!

# Anti member update
### Description
Enabling anti member update restricts user from updating their/others role with dangerous permission in guild.

### Usage
!!!primary
`-antimemberupdate <on/off>`
--![antimember update on](../../img/Commands/AutoMod/antimemberupdateon.png)--
--![antimember update off](../../img/Commands/AutoMod/antimemberupdateoff.png)--
!!!

# Anti public role
### Description
adding role in antipublic role list will restrict users from tagging that role in guild. for example [**@faimly**] role if added then users trying to tag that role will trigger the bot.

### Usage
!!!primary Add/Remove role to/from antipublic role list
`-antipublicrole <add/remove> @role/role ID`
--![antipublic role add](../../img/Commands/AutoMod/antipublicadd.png)--
--![antipublic role remove](../../img/Commands/AutoMod/antipublicoff.png)--
!!!

!!!primary Show current antipublic role list
`-antipublicrole`
--![antipublic role list](../../img/Commands/AutoMod/antipublic.png)--
!!!

# Anti role create
### Description
sets limit on how many role creations will trigger the bot. For example [**-antirolec 2**] bot will get triggered when someone creates second role in guild and bot will take action against that user.

### Usage
!!!primary Set limit
`-antirolec <1/2/3/4/...>`
--![antirole create limit](../../img/Commands/AutoMod/antirolec.png)--
!!!

!!!primary Disable
`-antirolec off`
--![antirole create off](../../img/Commands/AutoMod/antirolecoff.png)--
!!!

# Anti role delete
### Description
sets limit on how many role deletions will trigger the bot. For example [**-antiroled 2**] bot will get triggered when someone deletes second role in guild and bot will take action against that user.

### Usage
!!!primary Set limit
`-antiroled <1/2/3/4/...>`
--![antirole delete limit](../../img/Commands/AutoMod/antiroled.png)--
!!!

!!!primary Disable
`-antiroled off`
--![antirole delete off](../../img/Commands/AutoMod/antiroledoff.png)--
!!!

# Anti role update
### Description
Enabling this restrict users from updating role permissions in guild.

### Usage
!!!primary
`-antiroleu <on/off>`
--![antirole update on](../../img/Commands/AutoMod/antiroleuon.png)--
--![antirole update off](../../img/Commands/AutoMod/antiroleuoff.png)--
!!!

# Anti self bot
### Description
Enabling this will restrict users from selfbotting in guild.

### Usage
!!!primary
`-antiselfbot <on/off>`
--![antiselfbot on](../../img/Commands/AutoMod/antiselfboton.png)--
--![antiselfbot off](../../img/Commands/AutoMod/antiselfbotoff.png)--
!!!

# Anti unverified bot
### Description
Enabling this will restrict users from adding unverified bots in guild.

### Usage
!!!primary
`-antiunverifiedbot <on/off>`
--![antiunverifiedbot on](../../img/Commands/AutoMod/antiunverion.png)--
--![antiunverifiedbot off](../../img/Commands/AutoMod/antiunverioff.png)--
!!!

# Anti webhook
### Description
Enabling this will restrict users from creating webhooks in guild.

### Usage
!!!primary
`-antiwebhook <on/off>`
--![antiwebhook on](../../img/Commands/AutoMod/antiwebon.png)--
--![antiwebhook off](../../img/Commands/AutoMod/antiweboff.png)--
!!!