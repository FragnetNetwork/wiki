You will need first to become admin to be able to use commands described in the article. Guide for becoming admin can be found here.

# List of Admin Chat Commands:

To use these commands, simply log into your server and open the text chat in-game. Type your command and hit "Enter" to execute the command. Text commands can also be used when in Spectator Mode.

Optional parameters can be added anywhere inside the command and will change the way the command works. One Example is `/teleport` - By default, it teleports safely, making sure the player is on ground and not inside anything. But the keyword `unsafe` will stop the teleport from checking for a safe location.

When creating player roles, the permission to allow any command is the name of the command unless otherwise stated, for example, `/bring` relies on the "teleport" permission, so you must allow that permission in order for a role to use `/bring`.

## Everyone's Commands:
Commands in this section do not require permission to use.

Command | Description
--- | ---
`/rules` | Lists the server's rules.
`/motd`  | Displays the server's Message of The Day.
`/help`  | Lists all the commands that player has access to with a short description of each.
`/clear`  | Clears the current chat channel.
`/mapbug`  | Copies the current player position to the clip board.
`/bugsnap`  | Loads a dialogue for submitting a bug snapshot.
`/respawn`  |  Kills your character and respawns them at a standard spawn point. Useful if players somehow get stuck.
`/mute <user>`  |  Mutes the specified user. This only mutes them for the player, not the entire server.
`/unmute <user>`  | Unmutes the specified user. This only unmutes them for the player, not the entire server.
`/listplayers`  | Shows all players on the server.
`/whisper [Username] [Message]`  | Whispers a message to the specified player. If no player is specified, it will whisper to the last player you whispered to.
`/w [Username] [Message]`  | Shortcut for /whisper.

## Teleports:

Command | Example | Description | Permission
--- | --- | --- | ---
`/teleport (coordinates)`  | `/teleport (X=-91112.6875,Y=-176182.75,Z=13156.462891)` | Teleports yourself to the specified coordinates. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport | `+Permission=teleport` 
`/teleport <user> (coordinates)`  | `/teleport Jiggy (X=-91112.6875,Y=-176182.75,Z=13156.462891)`| Teleports the user to the specified coordinates. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport | `+Permission=teleport` 
`/teleport <user> <user>`  | `/teleport Bob Steve` | Teleports the first user to the second user. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport | `+Permission=teleport` 
`/teleport <POIname>` | `/teleport talonspoint` | Teleports yourself to a point within the specified POI. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport | `+Permission=teleport` 
`/teleport <user> <POIname>`  | `/teleport Jiggy talonspoint` | Teleports the user to a point within the specified POI. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport | `+Permission=teleport` 
`/bring <user>` | `/bring Jiggy` | Brings the user to your location. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport  | `+Permission=teleport` 
`/goto <location>` | `/goto talonspoint` | Teleports you to the target location. The location can be either a username, a POI, or coordinates. `unsafe` Optional parameter, use to change from a safe teleport to an unsafe teleport | `+Permission=teleport`
`/teleportall <POIname>` | `/teleportall talonspoint` | Teleports all users on the server to a point within the specified POI. | `+Permission=teleportall` 
`/teleportall (coordinates)`  | `/teleportall (X=-91112.6875,Y=-176182.75,Z=13156.462891)` | Teleports all users on the server to the specified coordinates. | `+Permission=teleportall`
`/bringall` | `/bringall` | Teleports all players to your location. |   `+Permission=teleportall`

## Change Stats:

Command | Example | Description | Permission
--- | --- | --- | ---
`/setmarks <number>` | `/setmarks 900` | Sets your marks to the specified number. | `+Permission=setmarks` 
`/setmarks <user> <number>` | `/setmarks Jiggy 900` | Sets a players marks to the specified number. | `+Permission=setmarks` 
`/addmarks <user> <number>` | `/addmarks Jiggy 200 ` | Add a number of marks to the player. | `+Permission=setmarks` 
`/removemarks <user> <number>` | `/removemarks Jiggy 400` | Removes a number of marks from the player. | `+Permission=setmarks` 
`/heal` | `/heal` | Heals yourself. | `+Permission=heal` 
`/heal <user>` | `/heal Jiggy` | Heals the specified player | `+Permission=heal` 
`/healall` | `/healall`| Heals everyone. | `+Permission=healall`
`/godmode` | `/godmode` | Apply godmode to yourself. Use this command again to toggle it on/off. | `+Permission=godmode` 
`/godmode <user>` | `/godmode Jiggy` | Apply godmode to a user. Use this command again to toggle it on/off. | `+Permission=godmode` 
`/<attribute> <number>` | `/hunger 100` | Sets your hunger to 100. Use `/hunger <user> 100` to set a user's stats. Other examples: `/thirst 300`  `/stamina Jiggy 50` `/oxygen 20` | `+Permission=modify attribute`
`/modattr <user> <attribute> <value>` | `/modattr Jiggy Stamina -100` | Modifies the user's attribute by the value specified. This is additive, rather than `/setattr`, which overrides the value. Some common attributes are `Health` `MaxHealth` `Stamina` `Hunger` `MaxHunger` | `+Permission=modify attribute`
`/setattr <user> <attribute> <value>` | `/setattr Jiggy Stamina 20` | Sets the user's attribute to the value specified.  | `+Permission=set attribute`
`/givequest <user> <questname>` | `/givequest Jiggy Collect Mushrooms` | Assigns the specified quest to that player. | `+Permission=givequest` 

## Admin Tools:

Command | Example | Description | Permission
--- | --- | --- | ---
`/save` | `/save` | Forces a server save. | `+Permission=save` 
`/promote <user> <adminrole>` | `/promote Jiggy dinomaster` | Promotes the player to the specified admin role. | `+Permission=promote` 
`/demote <user>` | `/demote Jiggy` | Removes all admin roles of that player. | `+Permission=promote` 
`/kick <user> <kickreason>` | `/kick Jiggy Spamming the chat.` | Kicks the user with a message. You can optionally leave the message blank. | `+Permission=kick` 
`/ban <user> <banreason>`  | `/ban Jiggy Breaking rule number 12` | Bans the user with a message. You can optionally leave the message blank. | `+Permission=ban` 
`/restart <seconds>` |  `/restart 120` | Restarts the server after the specified number of seconds. | `+Permission=restart` 
`/cancelrestart` | `/cancelrestart` | Cancels the server restart. | `+Permission=restart`
`/announce <message>` | `/announce Everyone kill Jiggy for bonus points!` | Makes an announcement to everyone on the server. | `+Permission=announce` 
`/listpoi` | `/listpoi` | Lists all the POIs on the current map. | `+Permission=listpoi` 
`/listquests` | `/listquests` | Lists all quests currently available. | `+Permission=listquests`
`/listroles` | `/listroles` |Lists all roles currently available. | `+Permission=listroles` 
`/listwaters` | `/listwaters` | Lists all bodies of water on the map. | `+Permission=listwaters`
`/listwaystones` | `/listwaystones`  | Lists all waystones on the map. | `+Permission=listwaystones` 
`/weather <type>` | `/weather clearsky` | Sets the weather to the specified weather type. Types available are: `ClearSky` `Overcast` `Fog` `Cloudy` `Rain` and `Storm` | `+Permission=weather` 
`/timeofday <time>` | `/timeofday night` | Sets the time of day. Available times are `morning` `night` `day` and optionally you can specify a number for more precise time, example: `/timeofday 2000`. Midday is `1200` and midnight is `2400` or `0`. | `+Permission=time of day`
`/day` | `/night` | Shorthand for `/timeofday night`. Other shorthand time commands are `/day` and `/morning` | `+Permission=time of day` 
`/clearbodies` | `/clearbodies` | Clears all dead bodies from the map. | `+Permission=clearbodies`
`/waterquality <tag> <0-100%>` | `/waterquality swampyreservoir 50` | Sets the water body of the tag specified to a percentage quality. |  `+Permission=waterquality` 
`/waystonecooldown <tag> <0-100%>` | `/waystonecooldown centralwaystone 50` | Sets the waystone of the tag specified to a percentage cooldown remaining. | `+Permission=waystonecooldown` 
`/playerinfo <username/AGID>` | `/playerinfo 123-456-789` | Shows player info. | `+Permission=playerinfo` 
`/servermute <username/AGID> <time> <admin reason> <user reason>` | `/servermute 123-456-789 20m "reason for admin" "reason for muted player"` | Mutes a player server wide. Time is specified in minutes, hours or days. e.g. 20m, 4h or 1d. If 0 is given for time, it will be forever. | `+Permission=servermute` 
`/ServerUnmute <username/AGID>` | `/serverunmute 123-456-789` | Removes a server wide mute for a player. | `+Permission=serverunmute` 
`/Whitelist <username/AGID>` | `/whitelist 123-456-789` | Adds a player to the whitelist for the server. | `+Permission=whitelist` 
`/DelWhitelist <username/AGID>` | `/delwhitelist 123-456-789` | Removes a player from the server whitelist. | `+Permission=delwhitelist` 
`/ReloadBans` | `/reloadbans` | Reloads server bans from the ban file. | `+Permission=reloadbans`
`/ReloadMutes` | `/reloadmutes` | Reloads server mutes from the mutes file. | `+Permission=reloadmutes` 
`/ReloadWhitelist` | `/reloadwhitelist` | Reloads server whitelist. | `+Permission=reloadwhitelist`  
`/ClearCreatorObjects` | `/clearcreatorobjects` | Removes and refunds all placed Creator Mode Objects on the server. | `+Permission=clearcreatorobjects` 
`/LoadCreatorMode <SaveName>` | `/loadcreatormode rockworld` | Loads the saved Creator Mode data from the specified save slot. | `+Permission=loadcreatormode`  
`/SaveCreatorMode <SaveName>` | `/savecreatormode rockworld` | Saves the Creator Mode data to the specified save slot. | `+Permission=savecreatormode` 
`/ResetCreatorMode` | `/resetcreatormode` | Resets Creator Mode Objects to their default, removing placed objects and changing map objects to their original state. | `+Permission=resetcreatormode`  
`/RemoveCreatorMode <SaveName>` | `/removecreatormode rockworld` | Removes the Creator Move data from the specified save slot. | `+Permission=removecreatormode`  
`/ListCreatorMode` | `/listcreatormode` | Lists the saved Creator Mode saves. | `+Permission=listcreatormode`  