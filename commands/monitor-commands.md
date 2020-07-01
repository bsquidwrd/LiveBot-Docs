# Monitor Commands

All of the commands are meant to be after a mention of the bot `@Live Bot`   
Example: `@Live Bot help` where `help` is the command here.

## monitor start \[stream url\]

Aliases: `edit, add`

Start the process of creating/editing a monitor process for a stream

## monitor stop \[stream url\]

Aliases: `end, remove`

Stop monitoring a stream

## monitor list

List all the streams that are being monitored for the Discord Server

## monitor check &lt;stream url&gt;

See if the bot recognizes a stream as online or offline  
NOTE: To save resources on the bot, the channel has to be monitored in AT LEAST 1 Discord Server, otherwise this will always return Offline

## monitor perms

Aliases: `test`

Make the bot perform a self check of its permission for the channel the command was run

