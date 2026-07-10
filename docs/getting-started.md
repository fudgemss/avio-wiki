# Getting Started

## Inviting Avio Bot

To begin using Avio Bot, you need to invite it your server.
This can be done using the steps below:

1. Head to [Avio's Invite Link](https://aviobot.app/invite) and Log In with Discord
2. Select the server you wish to add Avio to
3. Accept the permissions Avio is requesting
4. Once added, ensure Avio has the required permissions
5. Avio has been successfully added to your server

!!! warning "Trusted Users Only"
        Only give the ability to add external apps to trusted users. Unauthorised use of this permission can result in
        your server being raided, and potentially destroyed.
        
        Team Avio is not liable for any accidental invite of Avio Bot to your server.
  

 ## Server Settings 

Before you can use Avio's features, there are a few settings you need to setup first to allow all other features to work.

## Configuring Server Channels

Before you can begin creating flights, you need to configure a channel they will be sent to, along with any staff information.
To do this, follow the steps below:

1. Run the commands [`/server-setup flights-channel [channel]`] and [`/server-setup staff-channel [channel]`].
2. Select the channels you wish to have your messages sent to.
3. Channels successfully configured.

If you wish to change these channels, simply run the command again and select a new channel.
An alert will popup if you already have channels configured, asking if you are 100% sure you wish to change the channels.

## Configuring Server Roles

Avio has its own built-in permission plugin, allowing you to lock commands behind certain roles.
To use this, you will need to assign a admin role and flight manager role.
You can do this through the steps below:

1. Run the command [`/server-setup roles [flight-role] [admin-role]`].
2. Select the roles you wish to assign to the permissions plugin.
3. Roles successfully configured.

If you wish to change these roles, simply run the command again and select a new set of roles.
An alert will popup if you already have roles configured, asking if you are 100% sure you wish to change the roles.

!!! danger "Permission Plugin"
        The **admin** role has access to all commands, only give this to trusted users.
        The **flight** role only has access to flight mangement tools.

---

!!! tip "View Configured Settings"
        You can view your configured settings using the command [`/config`] or by visiting the [dashboard](https://dashboard.aviobot.app).

