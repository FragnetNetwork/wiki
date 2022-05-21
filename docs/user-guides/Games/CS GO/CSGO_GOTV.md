GOTV can be enabled on every CS:GO server. GOTV allows you to watch a game currently in progress with some perks which you wouldn't usually have on the server as spectator.

**Enabling GOTV**  
  
There are 2 ways to enable GOTV on Fragnet servers:

1.  Enable it via control panel by going to configuration files and editing server.cfg with "Configuration editor"  
    ![](https://fragnet.atlassian.net/wiki/download/thumbnails/76022045/fragnetgotvoptions.png?version=2&modificationDate=1590679323186&cacheVersion=1&api=v2&height=150 "Knowledge base > CS:GO GOTV > fragnetgotvoptions.png")
2.  Manually adding the following commands to server.cfg:  
    
    tv\_enable "1"           //Enables GOTV
    tv\_autorecord "0"       //1 automatically records 
    tv\_maxclients "10"      //Defines the number of concurrent connections to your GOTV 
    tv\_delay "90"           //Specifies the delay for the GOTV stream
    tv\_advertise\_watchable 1
    

After making any kind of changes to server.cfg, you should restart your server so those changes can apply.

GOTV will have the same IP address as the server, but the port number will be different. To connect to GOTV, you need the IP address and port for the GOTV server. For Fragnet servers GOTV port usually goes +1 on the first digit from the server port. For example:  
Server IP is : x.x.x.x:27015, GOTV will be x.x.x.x:37015

  

### GOTV status

You can check if your GOTV is working by simply writing the following command in your console (while you are on the server): **rcon status.** If everything is setuped correctly you'll have the following output

![](https://fragnet.atlassian.net/wiki/download/thumbnails/76022045/fragnetgotv.png?version=1&modificationDate=1590682072655&cacheVersion=1&api=v2&height=183 "Knowledge base > CS:GO GOTV > fragnetgotv.png")

### Demos

If not setuped to automatically record, you can manually start and stop recording your matches on the server by typing the following commands:

*   tv\_record nameoftherecording - Starts GOTV demo recording with the name you specified
*   tv\_stoprecord - Stops GOTV demo recording with the name you specified 

If you have any GOTV recordings, you will find them in /csgo/ folder when you access it via File manager (on Game panel) or FTP Client. The files are saved in the **.dem** format.

### GOTV Cvars 
  
|      **Command**      |  **Value** |                             **Description**                            |
|:---------------------:|:----------:|:----------------------------------------------------------------------:|
|  tv_allow_camera_man  |    <0-1>   |          Auto director allows spectators to become camera man          |
| tv_allow_static_shots |    <0-1>   |            Auto director uses fixed level cameras for shots            |
|     tv_autorecord     |    <0-1>   |              Automatically records all games as GOTV demos             |
|      tv_autoretry     |    <0-1>   |          Relay proxies retry connection after network timeout          |
|    tv_chatgroupsize   |   <0-255>  |                     Set the default chat group size                    |
|    tv_chattimelimit   |      8     |             Limits spectators to chat only every n seconds             |
|       tv_clients      |     cmd    |                  Shows list of connected GOTV clients                  |
|        tv_debug       |     cmd    |                             GOTV debug info                            |
|        tv_delay       |     90     |                     GOTV broadcast delay in seconds                    |
|   tv_delaymapchange   |    <0-1>   |              Delays map change until broadcast is complete             |
|     tv_deltacache     |      2     |                  Enable delta entity bit stream cache                  |
|    tv_dispatchmode    |    <0-2>   | Dispatch clients to relay proxies: 0=never, 1=if appropriate, 2=always |
|       tv_enable       |    <0-1>   |                        Activates GOTV on server                        |
|     tv_maxclients     |  <0..255>  |                  Maximum client number on GOTV server                  |
|       tv_maxrate      |   196608   |        Max GOTV spectator bandwidth rate allowed, 0 == unlimited       |
|         tv_msg        |   <text>   |                  Send a screen message to all clients                  |
|        tv_name        |   <text>   |                             GOTV host name                             |
|   tv_overridemaster   |    <0-1>   |                 Overrides the GOTV master root address                 |
|        tv_port        |   <port>   |                             Host GOTV port                             |
|       tv_record       |   <text>   |                       Starts GOTV demo recording                       |
|        tv_relay       |  <ip+port> |               Connect to GOTV server and relay broadcast               |
|    tv_relaypassword   | <password> |                     GOTV password for relay proxies                    |
|     tv_relayvoice     |    <0-1>   |                      Relay voice data: 0=off, 1=on                     |
|        tv_retry       |     cmd    |                     Reconnects the GOTV relay proxy                    |
|    tv_snapshotrate    |     16     |                    Snapshots broadcasted per second                    |
|       tv_status       |     cmd    |                         Show GOTV server status                        |
|        tv_stop        |     cmd    |                        Stops the GOTV broadcast                        |
|     tv_stoprecord     |     cmd    |                        Stops GOTV demo recording                       |
|       tv_timeout      |     30     |                   GOTV connection timeout in seconds                   |
|        tv_title       |   <text>   |                     Set title for GOTV spectator UI                    |
|     tv_transmitall    |      1     |             Transmit all entities (not only director view)             |