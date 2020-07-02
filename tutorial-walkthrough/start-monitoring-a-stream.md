---
description: >-
  The below steps walk you through how to start monitoring a stream for your
  discord!
---

# Start Monitoring a Stream

## Information

* Do NOT type `<>` or `[]` 
* `<` and `>` mark Required Parameters
* `[` and `]` mark Optional Parameters
* If the bot is online and not responding to your commands, make sure it has `Send Messages` permission in the channel you are running the commands.

## Step 1 - Check Permissions

In the channel you will want to have notifications sent to, run the following command to ensure the bot has the appropriate permissions. If the bot doesn't respond, you must assign it AT LEAST `Send Messages` permission for the channel before you are able to check the rest of the permissions.

```text
@Live Bot monitor perms
```

The bot will either tell you what permissions it is missing or tell you that you are all set. If the bot is missing permissions for that channel, please grant them before proceeding.

## Step 2 - Start Monitoring

Initiate the setup process by running the following command

```text
@Live Bot monitor start [stream url]
```

## Step 3 - Stream URL

If you didn't enter a `[stream url]`, the bot will ask you for the link to the stream you wish to start monitoring.  
Example: [https://twitch.tv/bsquidwrd](https://twitch.tv/bsquidwrd)

## Step 4 - Discord Channel to notify

Next up is which channel you wish to send notifications to \(make sure you ran Step 1 in the channel\).  
Mention the channel \(prefixed with a `#`\), like this `#live`

## Step 5 - Notification Message

Now you get to customize the message the bot will send when the stream goes live!  
The available parameters for the notification message are below.  
  
These will get replaced by the bot before it sends a message, you DO NOT have to edit them. Simply place them in the message you want to use.  
  
You do have to type them exactly how you see them \(including the `{}`\) in the message, like `{name}` will get replaced with the Streamers username when the message is sent.  
If you don't want to type up your own, you can respond with `default` to get the below message  
Note: `{role}` will result in nothing if you choose `none` on the next step.

### Parameters

> {role} - Get replaced with the Role to ping \(if applicable\)  
> {name} - Gets replaced with the Streamers Name  
> {game} - Gets replaced with the Game they are playing  
> {url} - Gets replaced with a link to the Stream  
> {title} - Gets replaced with the Stream Title

### Default

`{role} {name} is live and is playing {game}! {url}`

### Example

If you typed `Yo {role}, come checkout {name} while they play {game} over at {url}`, that would result in `Yo @LiveSquad, come checkout bsquidwrd while they play Overwatch over at https://twitch.tv/bsquidwrd`

## Step 6 - Role to ping

You're almost there! The last step is choosing a role to ping.  
This accepts the name of the role to prevent unnecessary/unwanted pings.  
If you want to ping @everyone simply respond with `everyone` \(without the @\)  
If you don't want to ping a role, you can respond with `none` and it won't ping anyone.  
Even if you answer with a role to ping, if you didn't include the `{role}` variable in the message the bot will not ping anyone

## Step 7 - Finished

As long as the bot didn't tell you there was an error anywhere, you're good to go!

