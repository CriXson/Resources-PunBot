# PunBot
## What is PunBot?
PunBot is a bot for Twitch.tv and Hitbox.tv streams. It prints a random pun every know and then to your chat to make everyone laugh and enjoy their stay even more!

## How to get PunBot?
In order to get PunBot to join your channel you just have to visit the respective PunBot channel for either Twitch.tv or Hitbox.tv and type "<b>!join [setup]</b>" into the chat.

- <a href="http://hitbox.tv/ThePunBot">PunBot on Hitbox.tv</a>
- <a href="http://twitch.tv/ThePunBot">PunBot on Twitch.tv</a> (WIP!)

All possible options for <b>[setup]</b> are listed here:

[setup]   |Description
----------|-------------
de        |German language
en		  |English language
... More coming soon!

## What commands does PunBot have and how can I use them?

The commands of PunBot are focusing on adding a huge variety of customization options for streamers while still keeping it very simple and easy to understand.

Command   |Description
----------|-------------
!pun      |Prints a random pun to the chat.
!punEdit  |Use with "[setting] [param]" to update the settings.
!punInfo  |Prints the current version of PunBot to the chat.

In order to provide customization options, there are a couple of channel specific settings you should know about:

Setting   |Required Parameter|Default|Description
----------|------------------|-------|------------
cooldown  |Cooldown for <i>!pun</i>-Command in seconds.|60|Determines the cooldown of the command in between uses.
interval  |Cooldown for random pun in minutes.         |10|Delay between random pun in minutes.
setup     |One of the possible <i>setup</i> options.   |- |Allows to changes the initial option.
