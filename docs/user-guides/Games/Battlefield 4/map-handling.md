Overview
--------

BF4 PC game servers are designed to rotate through a sequence of maps. The exact configuration is specified in the server’s internal map list. Different maps in the map list can use different game modes. (Note however, that some game modes will not work properly if there are more players on the server than the game mode is designed for.)

Upon startup, the MapList.txt file is read. During runtime, the mapList.\* commands can be used to edit the set of maps.

When the same map is played for several rounds, all 2-team game modes stipulate that the teams will switch sides after a run. This way, a 2-round session of Rush will have players play both attackers and defenders.

Controlling map switching (via console)
---------------------------------------

*   mapList.\* can be used to edit the map list while the server is running.
    

*   mapList.setNextMapIndex sets which will be the next map.
    

*   mapList.getMapIndices returns information on which is the current and next map in the list.
    

*   mapList.runNextRound switches to the next round, without finishing the current.
    

*   mapList.restartRound makes all players reload the current map, and restarts the current round.
    

*   mapList.endRound declares a specific team as the winning team, and then moves directly to the end-of-round screen.
    

Maplist.txt format
------------------

Maplist can also be configured by editing Maplist.txt via Configuration Files in the game-panel.  
Each line in the file has three entries: the map name, the game mode, and the number of rounds to be played on the map until proceeding to the next map in the list.

Example Maplist.txt:  

|          **Line**         |                                   **Description**                                  |
|:-------------------------:|:----------------------------------------------------------------------------------:|
| MP_Siege ConquestLarge0 1 | The first one round of Conquest will be played on Siege of Shanghai.               |
| MP_Naval Obliteration 1   | Followed by one round of Obliteration on Parcel Storm, this sequence then restart. |

Editing Maplist.txt with Procon Layer
-------------------------------------

Maplist can also be configured with the Procon Layer.  
In fact, it might be the easiest way to configure your maplist this way as it provides a GUI, where you add the maps with a simple click, rather than writing the lines in the config.  
For more information please refer to this article: [Setting up Maplist via Procon]