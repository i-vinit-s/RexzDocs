---
label: Configuration # Label - shows at navigation tab
order: 850 # Page order in folder
icon: gear # Page icon - shows at navigation tab
author: # Who written this page
  name: BxBY # Author name
  avatar: ./img/bxby.jpg # Author avatar
meta: # Meta tag - works like <meta>
  title: "Custom Configuration" # Page title (this will override default meta.title set in config)
description: "Customize RexZ to fit your server's needs with our easy-to-use configuration settings. Adjust security levels, moderation tools, and automation features for optimal protection and control." # Page description
category: [setup, config] # Page category (might be multiple categories - [category1, category2])
route: "/config/" # Change default route set by retype
---

The configuration allows you to customize RexZ to suit your server's security and moderation needs. Adjust settings for Anti-Nuke protection, moderation commands, security alerts, and more. With easy-to-use controls, you can fine-tune RexZ to provide the perfect balance of automation and protection, ensuring a safe and well-managed community.

## Prefix

!!!secondary
Default prefix is `-`
!!!

[Click here](./Commands/Moderation/Setprefix.md) to know more about **prefix**.

## Logs Channel

!!!secondary
Log channel was created by bot while setup,
You can also update it by yourself
!!!

[Click here](./Commands/Security/Logs.md) to know more about **How to add/update logs channel**.

## Threat Mode

!!!secondary
When the bot's threat mode is enabled, any action taken by a whitelisted member will trigger the bot.
!!!

Example :-
If a whitelisted member kicks someone while threat mode is enabled, they will also be kicked by the bot.

[Click here](./Commands/Security/Threatmode.md) to know more about **Threat mode**.

## Super Threat Mode

!!!secondary
When the bot's super threat mode is enabled, any action taken by a whitelisted member or second owner will trigger the bot, and the user who took the action will also be banned.
!!!

Example :-
If a whitelisted member or second owner kicks someone, they will also be kicked by the bot.

[Click here](./Commands/Security/Superthreatmode.md) to know more about **Super Threat mode**.

## Punishment Type

!!!secondary
Type of the punshment bot will give to user, i.e. ban, kick
!!!

[Click here](./Commands/Security/Punishment.md) to know more about **punishment**.

## Second Owner

!!!secondary
A user who have same permissions as owner of the bot (`excluded auto command`)
!!!

[Click here](./Commands/Trustables/Addowner.md) to know more about **How to add 2nd owner**.

[Click here](./Commands/Trustables/Removeowner.md) to know more about **How to remove 2nd owner**.

[Click here](./Commands/Trustables/Owner.md) to know more about **Available 2nd owner**.

## Whitelisted Users

!!!secondary
List of all users who are whitelisted for RexZ bot
!!!

[Click here](./Commands/Trustables/Whitelist.md) to know more about **How to whiteslist a user**.

[Click here](./Commands/Trustables/Unwhitelist.md) to know more about **How to unwhitelist a user**.

[Click here](./Commands/Trustables/Wlisted.md) to know more about **List of whitelisted users**.

## Admins

!!!secondary
List of users with admin permissions of RexZ bot.
!!!

[Click here](./Commands/Trustables/Addadmin.md) to know more about **How to add admin**.

[Click here](./Commands/Trustables/Removeadmin.md) to know more about **How to remove admin**.

[Click here](./Commands/Trustables/Admins.md) to know more about **List of admins**.

## Moderators

!!!secondary
List of users with mod permissions of RexZ bot.
!!!

[Click here](./Commands/Trustables/Addmod.md) to know more about **How to add moderator**.

[Click here](./Commands/Trustables/Removemod.md) to know more about **How to remove moderator**.

[Click here](./Commands/Trustables/Mods.md) to know more about **List of moderators**.

## Anti Unverified Bots

!!!secondary
It prevents server from adding any unverified bot.
!!!

Example: If it is enabled, no one can able to add unverified bot into the server.

## Anti Bot

!!!secondary
It prevents server from adding any type of bot.
!!!

Example: If it is enabled, no one can able to add bot into the server.

## Anti Channel Update

!!!secondary
It prevents server from updating any channel.
!!!

Example: If it is enabled, no one can able to update any channel in the server.

## Anti Role Update

!!!secondary
It prevents server from updating any role.
!!!

Example: If it is enabled, no one can able to update any role in the server.

## Anti Everyone

!!!secondary
It prevents server from mentioning `@everyone`.
!!!

Example: If it is enabled, no one can able to mention `@everyone` in the server.

## Anti Community

!!!secondary
It prevents server from updating any community settings.
!!!

Example: If it is enabled, no one can able to update community settings in the server.

## Anti Webhook

!!!secondary
It prevents server from creating/updating/deleting webhooks.
!!!

Example: If it is enabled, no one can able to create/update/delete webhook in the server.

## Anti Emoji

!!!secondary
It prevents server from adding/deleting emojis.
!!!

Example: If it is enabled, no one can able to add/delete emoji in the server.

## Anti Emoji Update

!!!secondary
It prevents server from updating any existing emoji.
!!!

Example: If it is enabled, no one can able to update any existing emoji in the server.

## Anti Member Update

!!!secondary
It prevents server from updating any member.
!!!

Example: If it is enabled, no one can able to update member in the server i.e. `set/remove nickname, add/remove role etc`.

## Anti Unban

!!!secondary
It prevents server from unbanning already banned user.
!!!

Example: If it is enabled, no one can able to unban any of already banned user.

## Anti Guild Update

!!!secondary
It prevents server from updtating server details.
!!!

Example: If it is enabled, no one can able to update server i.e `server name/description/icon/banner etc`.

## Anti Ban

!!!secondary
It prevents server from banning any user.
!!!

Example: If it is enabled, no one can able to ban any user from the server.

## Anti Kick

!!!secondary
It prevents server from kicking any user.
!!!

Example: If it is enabled, no one can able to kick any user from the server.

## Anti Role Create

!!!secondary
It prevents server from creating any role.
!!!

Example: If it is enabled, no one can able to create any role in the server.

## Anti Role Delete

!!!secondary
It prevents server from deleting any role.
!!!

Example: If it is enabled, no one can able to delete any role in the server.

## Anti Channel Create

!!!secondary
It prevents server from creating any channel.
!!!

Example: If it is enabled, no one can able to create any channel in the server.

## Anti Channel Delete

!!!secondary
It prevents server from deleting any channel.
!!!

Example: If it is enabled, no one can able to delete any channel in the server.

## Permissions

!!!warning NOTE
Whitelisted users/2nd owner are able to use these functions as per requirements (`every function have different permissions`). <br> Server owner is able to use all of these functions without getting any punishment.
!!!