---
description: >-
  The below steps walk you through how to start monitoring a stream for your
  discord!
---

# Start Monitoring a Stream

## Step 1

In the channel you will want to have notifications sent to, run the following command to ensure the bot has the appropriate permissions. If the bot doesn't respond, you must assign it AT LEAST `Send Messages` permission for the channel before you are able to check the rest of the permissions.

```text
@Live Bot#5263 monitor (test/perms)
```

The bot will either tell you what permissions it is missing or tell you that you are all set. If the bot is missing permissions for that channel, please grant them before proceeding.

## Step 2

Initiate the setup process by running the following command

```text
@Live Bot#5263 monitor (start/edit/add) [stream url]
```

## Step 3

If you didn't enter a `[stream url]`, the bot will ask you for the link to the stream you wish to start monitoring.  
Example: [https://twitch.tv/bsquidwrd](https://twitch.tv/bsquidwrd)

## Step 4

Next up is which channel you wish to send notifications to \(make sure you ran Step 1 in the channel\).  
Mention the channel \(prefixed with a `#`\), like this `#live`

## Step 5

Now you get to customize the message the bot will send when the stream goes live!  
The below are the parameters available for the notification message.

You do have to type them exactly how you see them \(including the `{}`\) in the message, like `{name}` will get replaced with the Streamers username when the message is sent.

> {role} - Role to ping \(if applicable\)  
> {name} - Streamers Name  
> {game} - Game they are playing  
> {url} - URL to the stream  
> {title} - Stream Title

If you don't want to type up your own, you can respond with `default` to get the below message  
`{role} {name} is live and is playing {game}! {url}`

Note: `{role}` will result in nothing if you choose `none` on the next step.

## Step 6

You're almost there! The last step is choosing a role to ping.  
This accepts the name of the role to prevent unnecessary/unwanted pings.  
If you want to ping @everyone simply respond with `everyone` \(without the @\)  
If you want to not ping a role, you can say `none` and it won't ping anyone

## Step 7

As long as the bot didn't tell you there was an error anywhere, you're good to go!

