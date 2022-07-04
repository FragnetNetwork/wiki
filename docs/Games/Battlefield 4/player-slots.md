How many players does a server support?
---------------------------------------

This is determined by four factors:

1.  The max-cap which is set according to the slots you have ordered for your game server, stated in your game panel.
    
2.  The admin (you) also has a max cap that can be set (**vars.maxPlayers**) in the server configuration (startup.txt), can be set between 0 to the max amount of slots you have purchased.
    
3.  During runtime the game engine will not allow the desired max-cap to be set to anything lower than the current number of players.
    
4.  Depending on game mode there may also be a commander on each team which are included in the maximum amount of players, and will take up your actual player slots, unless commanders are disabled, the same applies to spectators.
    

The current desired max number of players is the minimum of the max-cap and the **vars.maxPlayers** value. Normally the engine will accept runtime changes to the setting within a second. However, if the **vars.maxPlayers** setting is set to anything lower than the current number of players on the server, the effective max number of players on the server will remain unchanged. The server will then retry changing the effective max-cap every 10 seconds until it succeeds.