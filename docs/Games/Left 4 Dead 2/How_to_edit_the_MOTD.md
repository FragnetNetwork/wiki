MOTD or Message of the day is a small text that appears to players once they join the server.

Banners can also be added, but we’ll cover this in a different guide.

1. First, we’ll need to locate the MOTD. By default MOTD is located at `left4dead2 / motd.txt`.

![MOTD](../images/motd.png)

2. Once found, open it. There will be a link which you can remove it and add any message you wish for all players to see. 

![](../images/example-motd.png)

3. Once done, click on **Save Content** in the window's lower right corner.

4. Afterwards, we need to locate the server.cfg to enable the MOTD.The server.cfg is located in `left4dead2 / cfg / server.cfg`.
![](../images/serverconfig.png)
Once found, open it up and `insert motd_enable 1`. You can add it anywhere in between the codes ( keep it somewhere at the beginning for easier access like in the example ) and click on **Save Content** in the window's lower right corner.

![](../images/motd-enable.png)

5. Start/Restart the server and connect to it.