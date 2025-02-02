---
label: Security # Label - shows at navigation tab
order: 100 # Page order in folder
icon: shield-lock # Page icon - shows at navigation tab
author: # Who written this page
  - name: BxBY # Author name
    avatar: ../../img/bxby.jpg # Author avatar
meta: # Meta tag - works like <meta>
  title: "Security" # Page title (this will override default meta.title set in config)
description: "Discover all security commands of RexZ, including anti-nuke, raid protection, and advanced moderation tools. Keep your server safe with real-time monitoring and automated threat prevention." # Page description
category: [security, config, security, setup, commands] # Page category (might be multiple categories - [category1, category2])
tags: [antinuke, commands] # Tags to find page easily with search
route: "/security/" # Change default route set by retype
---

# RexZ Security

## What is RexZ Security?  
RexZ Security is a powerful module designed to **protect your server from nukes, raids, and unauthorized actions**. It includes **real-time monitoring, automated threat detection, and preventive measures** to ensure the safety of your community. With **customizable security settings and logging**, RexZ helps you stay in control and prevent malicious activities.

## Features  
- **Anti-Nuke Protection** – Prevents mass bans, role deletions, channel wipes, and other destructive actions.  
- **Advanced Moderation** – Blocks unauthorized bot additions, mass kicks, and unwanted role changes.  
- **Custom Security Rules** – Set specific limits for different actions, such as role creation, channel updates, and webhook usage.  
- **Logging & Monitoring** – Keep track of security events with detailed logs.  
- **Automated Punishments** – Automatically take action against rule violators.  

---

## Security Commands  

### Anti Ban  
#### What is AntiBan?  
Prevents mass banning of users by setting a limit on bans within a specified time frame.

{.compact}
Aliases   | Usage  
---       | ---  
antib     | antiban <limit/off>

---

### Anti Bot  
#### What is AntiBot?  
Blocks unauthorized bots from joining the server unless manually allowed by an admin.

{.compact}
Aliases   | Usage  
---       | ---  
botprotection   | antibot <on/off>  

---

### Anti Channel Create  
#### What is AntiChannelCreate?  
Sets a limit on the number of channels a user can create to prevent mass creation.

{.compact}
Aliases   | Usage  
---       | ---  
anticc, anticreatechannel    | antichannelcreate <limit/off>  

---

### Anti Channel Update  
#### What is AntiChannelUpdate?  
Restricts excessive modifications to channel settings within a short period.

{.compact}
Aliases   | Usage  
---       | ---  
anticu, antiupdatechannel    | antichannelupdate <limit/off>  

---

### Anti Channel Delete  
#### What is AntiChannelDelete?  
Prevents users from mass deleting channels by setting a limit.

{.compact}
Aliases   | Usage  
---       | ---  
anticd, antideletechannel    | antichanneldelete <limit/off>  

---

### Anti Community  
#### What is AntiCommunity?  
Blocks unauthorized activation of community features that could expose the server to spam.

{.compact}
Aliases   | Usage  
---       | ---  
anticom   | anticommunity <on/off>  

---

### Anti Emoji Create  
#### What is AntiEmojiCreate?  
Restricts users from adding too many emojis within a short time.

{.compact}
Aliases   | Usage  
---       | ---  
antiec    | antiemojicreate <limit/off>  

---

### Anti Emoji Update  
#### What is AntiEmojiUpdate?  
Limits excessive modifications to existing emojis.

{.compact}
Aliases   | Usage  
---       | ---  
antieu    | antiemojiupdate <limit/off>  

---

### Anti Emoji Delete  
#### What is AntiEmojiDelete?  
Prevents mass deletion of emojis by setting a limit.

{.compact}
Aliases   | Usage  
---       | ---  
antied    | antiemojidelete <limit/off>  

---

### Anti Everyone  
#### What is AntiEveryone?  
Blocks users from mass-mentioning `@everyone` or `@here`.

{.compact}
Aliases   | Usage  
---       | ---  
everyoneprotection    | antieveryone <on/off>  

---

### Anti Guild Update  
#### What is AntiGuildUpdate?  
Prevents unauthorized changes to the server name, icon, or settings.

{.compact}
Aliases   | Usage  
---       | ---  
antigu, antiguildupdate    | antiguildupdate <limit/off>  

---

### Anti Kick  
#### What is AntiKick?  
Restricts mass kicking of members by setting a limit.

{.compact}
Aliases   | Usage  
---       | ---  
antik     | antikick <limit/off>  

---

### Anti Member Update  
#### What is AntiMemberUpdate?  
Prevents unauthorized changes to user nicknames, roles, or profile settings.

{.compact}
Aliases   | Usage  
---       | ---  
antimu    | antimemberupdate <limit/off>  

---

### Anti Public Role  
#### What is AntiPublicRole?  
Stops users from modifying public roles without proper permissions.

{.compact}
Aliases   | Usage  
---       | ---  
antipr    | antipublicrole add @role
   x       | antipublicrole remove @role
   x       | antipublicrole 

---

### Anti Role Create  
#### What is AntiRoleCreate?  
Restricts mass role creation to prevent abuse.

{.compact}
Aliases   | Usage  
---       | ---  
antirc, anticreaterole    | antirolecreate <limit/off>  

---

### Anti Role Delete  
#### What is AntiRoleDelete?  
Prevents unauthorized users from mass deleting roles.

{.compact}
Aliases   | Usage  
---       | ---  
antird, antideleterole    | antiroledelete <limit/off>  

---

### Anti Role Update  
#### What is AntiRoleUpdate?  
Restricts excessive changes to role permissions.

{.compact}
Aliases   | Usage  
---       | ---  
antirupdate, antiroleedit    | antiroleupdate <limit/off>  

---

### Anti Unban  
#### What is AntiUnban?  
Prevents users from unbanning members without proper authorization.

{.compact}
Aliases   | Usage  
---       | ---  
antiu     | antiunban <limit/off>  

---

### Anti Unverified Bot  
#### What is AntiUnverifiedBot?  
Blocks unverified bots from being added to the server.

{.compact}
Aliases   | Usage  
---       | ---  
antibot, aub   | antiunverifiedbot <on/off>  

---

### Anti Webhook  
#### What is AntiWebhook?  
Prevents unauthorized creation or modification of webhooks.

{.compact}
Aliases   | Usage  
---       | ---  
antiwh    | antiwebhook <limit/off>  

---

## Additional Security Features  

### Night Mode  
#### What is NightMode?  
Enables a high-security mode during specific hours, restricting server changes.

{.compact}
Aliases   | Usage  
---       | ---  
x    | nightmode <on/off>  

---

### Punishment  
#### What is Punishment?  
Defines the action (ban/kick/timeout) to be taken against violators.

{.compact}
Aliases   | Usage  
---       | ---  
x    | punishment <ban/kick>  

---

### Set Anti-Nuke Log  
#### What is SetAntiNukeLog?  
Configures the logging channel for all security-related events.

{.compact}
Aliases   | Usage  
---       | ---  
antinukelog, nukelog      | setantinukelog #channel

---

### Setup  
#### What is Setup?  
Initializes security settings and configures protection measures.

{.compact}
Aliases   | Usage  
---       | ---  
x     | setup  
