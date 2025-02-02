---
label: Ticket System # Label - shows at navigation tab
order: 0 # Page order in folder
icon: comment # Page icon - shows at navigation tab
author: # Who written this page
  - name: BxBY # Author name
    avatar: ../../img/bxby.jpg # Author avatar
meta: # Meta tag - works like <meta>
  title: "Ticket System" # Page title (this will override default meta.title set in config)
description: "Streamline support with RexZ's Ticket System. Manage and resolve user issues efficiently by creating private ticket channels for seamless communication and problem-solving within your server." # Page description
category: [setup, config, commands] # Page category (might be multiple categories - [category1, category2])
tags: [ticket] # Tags to find page easily with search
route: "/ticket-system/" # Change default route set by retype
---

## What is Ticket System?
A ticket system in a Discord bot is a feature that allows users to create and manage support requests within a Discord server. When a user creates a ticket, the bot generates a dedicated channel or thread for the issue, where the user and support staff can communicate. The system manages permissions, ensuring privacy and organization, and may include features such as categorization, automated responses, logging, and notifications. This system streamlines the support process, making it more efficient and organized for both users and support staff.

## Commands
Command   | Description | Usage
:---   | :---: | ---:
ticketadd | Add a user to ticket  | `-ticketadd <@user>`
ticketremove | Remove a user from ticket | `-ticketremove <@user>`
ticketmoderole | Setup ticket mod role | `-ticketmodrole <@role>`
ticketsetup | Setup ticket system | `-ticketsetup`
ticketcategory | Update tickets category | `-ticketcategory <#category>`
ticketedit | Edit an existing ticket | `-ticketedit <ticketRefNo/Id>`

## Setting Up a Ticket System

Follow these steps to set up a ticket system in your Discord server:

1. **Run the `-ticketsetup` Command**:
   - Type `-ticketsetup` in your Discord server and send the message.

2. **Click the `Setup Form` Button**:
   - After running the command, a button labeled `Setup Form` will appear. Click this button to proceed.

3. **Fill Out the Modal Form**:
   - A modal form will appear. Fill in the following details:
     - **channelID**: The ID of the channel where the ticket panel will be created.
     - **managerRoleID**: The ID of the role that will manage and have access to the tickets.
     - **ticketPanelDescription**: A brief description of the ticket panel.
     - **ticketTitle**: The title of the newly created ticket.
     - **ticketDescription**: The description of the newly created ticket.

4. **Click the `Submit` Button**:
   - After filling in all the required details, click the `Submit` button to finalize the setup.

Your ticket panel setup is now successful. Users can start creating tickets using the configured system.

## Adding a User to a Ticket

To add a user to a ticket or give ticket access to a user, use the `-ticketadd` command.

### Syntax
```
-ticketadd <@user>
```

### Steps
1. **Identify the User**: Make sure you know the user you want to add to the ticket.
2. **Run the Command**: In the channel of the active ticket, type `-ticketadd` followed by the mention of the user.
   
   For example:
   ```
   -ticketadd @username
   ```

This will grant the specified user access to the ticket, allowing them to view and participate in the ticket's conversation.

## Removing a User from a Ticket

To remove a user from a ticket or revoke their access, follow these steps:

1. **Run the `-ticketremove` Command**:
   - In the relevant ticket channel, type the command `-ticketremove` followed by the mention of the user you want to remove.
   - Example syntax: `-ticketremove @username`

This command will remove the specified user's access to the current ticket.

## Adding a Ticket Category

To set up a ticket category where all tickets will be created, use the `-ticketcategory` command. Follow the syntax and steps below:

### Syntax
```
-ticketcategory <#category>
```

### Steps
1. **Run the `-ticketcategory` Command**:
   - In your Discord server, type the command with the appropriate category mention. For example, if you want to set "Support Tickets" as the category, type:
     ```
     -ticketcategory #SupportTickets
     ```

2. **Confirm the Category Setup**:
   - Once the command is executed, the bot will confirm that the ticket category has been set up. All new tickets will now be created under the specified category.

This setup helps organize and manage tickets efficiently within a designated category.

## Editing a Ticket Panel

To edit an existing ticket panel in your Discord server, follow these steps:

1. **Run the `-ticketedit` Command**:
   - Type `-ticketedit <ticketRefNo/Id>` in your Discord server and send the message.
   - Replace `<ticketRefNo/Id>` with the reference number or ID of the ticket panel you want to edit.

2. **Fill Out the Modal Form**:
   - Similar to the setup process, a modal form will appear. Fill in all the details that need to be updated:
     - **channelID**: The ID of the channel where the ticket panel is located.
     - **managerRoleID**: The ID of the role that manages the tickets.
     - **ticketPanelDescription**: A brief description of the ticket panel.
     - **ticketTitle**: The title of the newly created ticket.
     - **ticketDescription**: The description of the newly created ticket.

3. **Click the `Submit` Button**:
   - After updating all the required details, click the `Submit` button to apply the changes.

Your ticket panel has now been successfully edited with the new details.

## Adding a Ticket Mod Role

To add a ticket mod role in your Discord server, use the `-ticketmodrole` command. This command assigns the specified role the ability to manage tickets.

### Syntax
```
-ticketmodrole <@role>
```

### Steps

1. **Type the Command**:
   - In your Discord server, type `-ticketmodrole` followed by mentioning the role you want to assign as the ticket mod role. For example:
     ```
     -ticketmodrole @SupportTeam
     ```

2. **Send the Message**:
   - After typing the command with the role mention, send the message.

By doing this, the specified role will now have the permissions to manage tickets within the ticket system.