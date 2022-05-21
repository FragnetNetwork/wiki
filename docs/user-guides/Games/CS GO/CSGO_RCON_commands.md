This list contains most common RCON command in Counter Strike: Global Offensive  
Before being able to use any of these command you have to establish a connection to the server by typing the following command in to the console : **rcon\_password yourrconpassword  
  
|             **Command**            |                                                                **Description**                                                                |
|:----------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------:|
|  rcon_password <yourrconpassword>  | Login to a server as admin. Keep in mind if you want to use commands as admin, you'll need to use prefix 'rcon', example: 'rcon map de_dust2' |
| exec <Configuration-File-Name>.cfg |                              Execute the supplied configuration file and loads all containd settings and scripts.                             |
|         sv_rcon_maxfailures        |        Sets auto ban on false Rcon commands, for example when commands are issued without rcon login. Note: min=1; standard=10; max=20        |
|       sv_rcon_minfailuretime       |                                                      Reset time for sv_rcon_maxfailures.                                                      |
|         sv_rcon_minfailures        |                      Count of false rcon commands before sv_rcon_minfailuretime is over. Note: min=1; standard=5; max=20                      |
|         sv_rcon_banpenalty         |                                    Sets the ban time for failed rcon commands in seconds. Note: 0=Permanent                                   |
|             sv_password            |                                 Sets a password required for players to connect. Example: sv_password somepass                                |
|             mp_winlimit            |                                        Sets the rounds to win for a team to change the map. Note: 0=off                                       |
|             mp_buytime             |                                            Sets the buy time in seconds. Example: mp_buytime “0.40″                                           |
|         mp_autoteambalance         |                                       The teams are balanced to equal or +1 players. Note: 0=off; 1=on.                                       |
|             mp_c4timer             |                            Sets the time in seconds till the bomb explodes. Example: mp_c4timer “50″ = 50 seconds.                            |
|             mp_chattime            |                                    Sets the time till mesages fade out in seconds. Example: mp_chattime “5″                                   |
|           mp_fadetoblack           |                                   Sets whether the screen fades to black on death or not. Note: 0=off; 1=on                                   |
|              mp_decals             |                                  Count of details (for example blood and bullte holes). Note: 0=off; 2048=max                                 |
|            mp_freezetime           |                               Sets the freeze time at each round restart. Example: mp_freezetime “6″ = 6 seconds                              |
|           mp_friendlyfire          |                                                   Activate friendly fire. Note: 0=off; 1=on                                                   |
|          mp_hostagepenalty         |                                  Sets the maximum tolerated hostage kills. Note: 0=off; 1=1 Kill; 2=2 Kills.                                  |
|            mp_limitteams           |                                         Sets the maximum of team player difference. Note: 0=No Limit.                                         |
|            mp_roundtime            |                                      Sets the round time. Note: 3=3 Minutes; 2.5=2Min 30 Sec; 0=No Limit.                                     |
|            mp_maxrounds            |                                         Sets rounds to play before a mapchange. Note: 0=No Mapchange.                                         |
|             mp_chattime            |                                    Sets the time till mesages fade out in seconds. Example: mp_chattime “5″                                   |
|             mp_autokick            |                                              Kick inactive players from server. Note: 0=off; 1=on                                             |
|     mp_friendly_grenade_damage     |                                                Toggle granede friendly fire. Note: 0=off; 1=on                                                |
|             mp_tkpunish            |                                    Toggle punishment for a teamkill (sit for one round). Note: 0=off; 1=on                                    |
|            mp_startmoney           |                                     Sets the player starting currency. Example: mp_startmoney “800″ = 800$                                    |
|           sv_enablevoice           |                                                      Toggle voicechat. Note: 0=off; 1=on                                                      |
|             sv_alltalk             |                                        Toggle of voicechat is global or team related. Note: 0=off; 1=on                                       |
|           mp_restartgame           |                            Toggle map restart time in seconds. Example: mp_restartgame “2″ = Restart in 2 seconds.                            |
|             sv_password            |                                 Sets a password required for players to connect. Example: sv_password somepass                                |
|             mp_playerid            |                                   Toggles display of player names on focus. Note: 0=all; 1=team only; 2=off                                   |
|           mp_forcecamera           |                                  Toggles game view on death. Note: 0=all; 1=only team; 2=stay where you died.                                 |
|             sv_gravity             |                                                 Sets the gravitation intensity. Default is 800                                                |
|              sv_cheats             |                                                 Toggle cheats on the server. Note: 0=off, 1=on                                                |
|               noclip               |                       Become invulnerable and escape gravity. Note: only available if “sv_cheats″ set to higher than 0!                       |
|         mp_allowspectators         |                                               Toggles spectator mode allowed. Note: 0=off; 1=on                                               |
|             sv_pausable            |                                                    Toggle game pausable. Note: 0=off; 1=on                                                    |
|           rcon say <Text>          |                                                          Global message from server.                                                          |
|        changelevel <Mapname>       |                                                  Change the map. Example: changelevel de_dust                                                 |
|            map <Mapname>           |                                             Change map and kick all players. Example: map de_dust                                             |
|            mp_footsteps            |                                                       Stepping sounds. Note: 0=off; 1=on                                                      |
|                users               |                                                       List all players user ID and name.                                                      |
|                kick                |                                               Kicks a player. Example: kick playername; kick #id                                              |
|                banid               |                                    Ban a player by its ID for x minutes. Example: banid id x; x=0>permanent                                   |
|                banip               |                                     Ban a player by its IP for x minutes. Example: banip x; x=0>permanent                                     |
|                quit                |                                                              Restarts the server.                                                             |
|               reload               |                                                                Reloads the map.                                                               |
|               status               |                                              Lists all players on the server with their Steam ID.                                             |
|             sv_maxspeed            |                                                     Sets the maximum speed for all players                                                    |

 Full list of CS:GO Server commands can be found [here](https://developer.valvesoftware.com/wiki/List_of_CS:GO_Cvars).