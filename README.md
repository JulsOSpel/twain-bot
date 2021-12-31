# Twain Bot
> Twain is an advanced anonymous confessions Discord bot with unique and powerful functionality.

## Add the bot to your server

[Click here](https://discord.com/api/oauth2/authorize?client_id=926070077361631272&permissions=171866064960&scope=bot%20applications.commands) to add the bot to your server.

## User Commands

### new-identity

![demo-identity](resources/demo-identity.png)

Randomizes a user's anonymous identity! Each time you run it, you get a random color and emoji.

Note: The bot will require that you wait at least 5 minutes to get another identity if you have sent a confession since making the last one.

### confess **[confession]**

![demo-identity](resources/demo-confession.png)

Submits a confession to the designated confessions channel for the current server.

## Admin Commands

### set-confession-channel

Sets the confession channel for the current server.

### ban-confession **[message-link]** **[banned]**

Bans or unbans the original sender of the anonymous confession message from using the bot in current server.

### revoke-all-bans

Revokes all bans on bot usage in the current server.

## Report issues

Report bot issues (including feature requests) using the [issues](https://github.com/ethanent/twain-bot-issues/issues) tab in this repository.

By creating issues you agree that they may be used to improve the bot, without compensation to you.

## Moderation

Server admins can manage bans on anonymous confessions through multiple means, but they are not permitted to see who made a confession.

To ban an anonymous poster, admins provide the bot with the message link to the anonymous message.
