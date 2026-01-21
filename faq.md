# FAQ

### _Does Live Bot work with YouTube?_

* _Technically_, yes.\
  While Live Bot is only intended for Twitch, monitoring a YouTube live stream is possible.
  * **NOTE**:­ This setup is not reliable and may result in duplicate notification posts if Twitch alerts are setup.
* _**How do I setup YouTube notifications?**_
  * Run the [#monitor-role](commands/monitor-commands.md#monitor-role "mention") command, `/monitor role role-to-monitor`. Users with this set role will have their stream posted once their Discord status changes to "Streaming" (purple icon).
* _**How do I stop YouTube live posts?**_
  * Run the command, `/monitor role stop-monitoring:True`.

***

### _What's the difference between "monitor create" and "monitor role"?_

* `monitor create`: ­ Detailed posts for Twitch that include the stream's starting game/category. - \*_recommended_
* `monitor role`: ­ Simplified posts for Twitch or YouTube that only lists the stream's game as "Twitch" or "YouTube".

***

### _Can multiple roles be pinged?_

* Yes! The `{role}` parameter represents all roles selected to mention: If your message is, `{role} Hey, {name} is live! Check out the stream: {url}` and you selected a 'role1' and 'role2', the bot will mention both roles next to each other where `{role}` is present.

***

### _Is there a limit as to how many Twitch streams can be monitored?_

* Currently, there is not a maximum limit set. However, this may change.

***

## Still having issues?

Please join the [Live Bot support server](https://livebot.bsquid.io/support) and post your question in #help.
