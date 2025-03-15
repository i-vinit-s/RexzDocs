---
label: Administration # Label - shows at navigation tab
order: 150 # Page order in folder
icon: shield-lock # Page icon - shows at navigation tab
author: # Who written this page
  - name: BxBY # Author name
    avatar: ../../img/bxby.jpg # Author avatar
meta: # Meta tag - works like <meta>
  title: "Administration" # Page title (this will override default meta.title set in config)
description: "Take full control of your Discord server with RexZ’s powerful administration commands. Manage roles, moderation settings, command permissions, server configurations, and more. Automate tasks, enforce rules, and keep your community well-organized with ease." # Page description
category: [setup, config, commands] # Page category (might be multiple categories - [category1, category2])
tags: [administration, commands] # Tags to find page easily with search
route: "/administration/" # Change default route set by retype
---

Manage your Discord server efficiently with RexZ’s **Administration** commands. These tools allow you to configure roles, moderation settings, command permissions, server customization, and more.

## Autorole

### What is Autorole?
The **Auto-Assigning Role** feature in RexZ allows server administrators to automatically assign roles to new members upon joining. You can configure different roles for **humans, bots, all users, or alternate accounts**.  

{.compact}  
Aliases  | Usage  
---      | ---  
ar       | autorole
x        | autorole add @role
x        | autorole remove @role
x        | autorole format

---

## Ban  

### What is Ban?  
The **Ban** command allows administrators to **permanently remove** a user from the server. Once banned, they **cannot rejoin** unless unbanned.  

{.compact}  
Aliases  | Usage  
---      | ---  
x      | ban @user

---

## Disable Command

### What is Disable Command?  
The **Disable Command** feature allows server administrators to **disable specific bot commands** within the server. This is useful for preventing unnecessary or disruptive commands.  

{.compact}  
Aliases  | Usage  
---      | ---  
disablecmd | disablecmd [command_name]  
disablecommand | x
disable-cmd | x
disable-command | x 

---

## Editembed  

### What is Editembed?  
The **Edit Embed** command allows administrators to **modify existing embed messages** sent by the bot, without sending a new one.  

{.compact}  
Aliases  | Usage  
---      | ---  
x | editembed [message_id]

---

## Embed  

### What is Embed?  
The **Embed** command allows users to create and send **custom embed messages** in the server.  

{.compact}  
Aliases  | Usage  
---      | ---  
x    | embed

---

## Enable Command 

### What is Enable Command?  
The **Enable Command** feature allows administrators to **re-enable a previously disabled command** in the server.  

{.compact}  
Aliases  | Usage  
---      | ---  
enablecommand | enablecmd [command_name]    

---

## Hackban  

### What is Hackban?  
The **Hackban** command bans a user **before they even join** the server. It prevents a specific **Discord ID** from entering the server.  

{.compact}  
Aliases  | Usage  
---      | ---  
x  | hackban <@user/id/name>

---

## Invc  

### What is Invc?  
The **Invc** command allows administrators to **manage the invc role** for the server.  

{.compact}  
Aliases  | Usage  
---      | ---  
x     | invc @role
x     | invc off
x     | invc remove

---

## Kick  

### What is Kick?  
The **Kick** command removes a user from the server **without banning them**. They can rejoin with an invite.  

{.compact}  
Aliases  | Usage  
---      | ---  
x     | kick @user

---

## Noprefix  

### What is Noprefix?  
The **No Prefix** feature allows certain users to **use bot commands without a prefix**.  

{.compact}  
Aliases  | Usage  
---      | ---  
x | noprefix add @user [duration]
x | noprefix remove @user
x | noprefix list 

---

## Role  

### What is Role?  
The **Role** command allows administrators to **assign or remove roles** from users.  

{.compact}  
Aliases  | Usage  
---      | ---  
x     | role add/remove @user @role/roleId

---

## Roleicon  

### What is Roleicon?  
The **Role Icon** command adds an **emoji as an icon** to a specific role.  

{.compact}  
Aliases  | Usage  
---      | ---  
x | roleicon [roleName/roleId] [emoji]

---

## Servericon  

### What is Servericon?  
The **Server Icon** command allows administrators to **change the server’s icon** via command.  

{.compact}  
Aliases  | Usage  
---      | ---  
x | servericon

---

## Setprefix  

### What is Setprefix?  
The **Set Prefix** command lets you **customize the bot's prefix** in the server.  

{.compact}  
Aliases  | Usage  
---      | ---  
prefix | setprefix [new_prefix]  

---

## Settings  

### What is Settings?  
The **Settings** command provides a **detailed overview** of all bot configurations for the server.  

{.compact}  
Aliases  | Usage  
---      | ---  
config | settings
status | x
setting | x
configuration | x
