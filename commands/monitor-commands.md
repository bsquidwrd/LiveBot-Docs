# Monitor Commands

All of the commands are Slash Commands&#x20;

## monitor create

Start the monitoring a stream

## monitor delete

Stop monitoring a stream

## monitor list

List all the streams that are being monitored for the Discord Server

## monitor check

See if the bot recognizes a stream as online or offline\
NOTE: To save resources on the bot, the channel has to be monitored in AT LEAST 1 Discord Server, otherwise this will always return Offline

## monitor role

This will start the bot monitoring a Discord role in your server and post them to where you specify. The message used for this is the server default setup under `/config`

NOTE: This will post whenever someone with the selected role goes live (according to Discord with the Purple status icon). If you notice the "Game" in the post says "Twitch" or "YouTube" then that means the message was posted due to this setting. To disable it, choose the sub option `stop-monitoring` and select `True`
