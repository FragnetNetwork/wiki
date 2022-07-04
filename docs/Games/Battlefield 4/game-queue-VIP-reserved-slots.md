If a game server is full, people who try to join will be placed in a queue. There are some options to control how people are added from the queue.

Priority order:

1.  VIP players (players added to the reservedSlotsList)
    
2.  Premium players (players who have bought Premium)
    
3.  Normal players.
    

If players are added to the reservedSlotsList, they will be moved in ahead of normal and Premium players. If **reservedSlotsList.aggressiveJoin** is set to true and a VIP enters the queue the server will kick a non VIP from the game to make room for the queued VIP. The server will first try to kick a non-VIP player who is not in a group and first if no such player could be found will it kick a grouped non-VIP. When kicking players we do not make any distinguish between Premium and Normal players. A normal or Premium player joining the queue will never trigger a kick.

### ReservedSlotsList.txt format

Each line should have one player name. There can be a maximum of 500 entries in the list.

### Spectator list

If the game server is set to a server type lower than official, the spectator list can come in to use. On official, vars.alwaysAllowSpectators is set to true by default. If the server is hosted with another server type then this command can be set to false. If this is the case, then only players that are in the spectatorList.txt can join the server as a spectator.