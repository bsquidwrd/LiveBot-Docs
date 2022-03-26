---
description: >-
  The below steps walk you through how to start monitoring a stream for your
  discord!
---

# Start Monitoring a Stream

## Step 1 - Check Permissions

In the channel you will want to have notifications sent to, run the following command to ensure the bot has the appropriate permissions.

```
/perm-check
```

The bot will either tell you what permissions it is missing or tell you that you are all set. If the bot is missing permissions for that channel, please grant them before proceeding.

## Step 2 - Start Monitoring

Create the stream monitor by running the following command, but replace the values as you need

```
/monitor create profile-url:https://twitch.tv/bsquidwrd where-to-post:#live role-to-mention:@everyone
```

## Step 3 - Notification Message

You can customize the message the bot will send when the stream goes live!\
The available parameters for the notification message are below.\
\
These will get replaced by the bot before it sends a message, you DO NOT have to edit them. Simply place them in the message you want to use.\
\
You do have to type them exactly how you see them (including the `{}`) in the message, like `{name}` will get replaced with the Streamers username when the message is sent.\
If you don't want to type up your own, you can respond with `default` to get the below message\
Note: `{role}` will result in nothing if you choose `none` on the next step.

### Parameters

> {role} - Will be replaced with the Role to ping (if applicable)\
> {name} - Will be replaced with the Streamers Name\
> {game} - Will be replaced with the Game they are playing\
> {url} - Will be replaced with a link to the Stream\
> {title} - Will be replaced with the Stream Title

### Default Live Message

`{role} {name} is live and is playing {game}! {url}`

### Example

If you typed `Yo {role}, come checkout {name} while they play {game} over at {url}`, that would result in `Yo @LiveSquad, come checkout bsquidwrd while they play Overwatch over at https://twitch.tv/bsquidwrd`

To use a custom message, add the `live-message` option to the Slash Command before executing. If you missed it, that's okay! You can see [edit-monitoring-a-stream.md](edit-monitoring-a-stream.md "mention") to find out how to modify it if you'd like.
