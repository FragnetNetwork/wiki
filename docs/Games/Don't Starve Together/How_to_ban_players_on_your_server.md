There are two ways to ban players.

1. If the players are still present on the server, they can be banned via console commands.

2. Banning players via blocklist.txt.

# Banning players via console commands

In this example, we will use the game panel console, but you can also do this in-game.

1. Navigate to your Fragify console and type in the command: ```c_listallplayers()```. It will list all players and their Klei IDs.

2. Once you have found the player copy their Klei ID In this command: ```TheNet:Kick("PlayerKleiID")``` 
>Leave the apostrophes and the parenthesis they are needed.

It should look something like this:
```TheNet:Kick("KU_ex12312")```. Once executed the player is banned.

# Banning players via Blocklist.txt

1. If the player isn’t online anymore, you can go to the server logs, search for the player's name and find their Klei ID.
The server logs are located at `DoNotStarveTogether => config => server => Master => server_log.txt`.

2. Now, we need to go to the directory where blocklist.txt is, and if it isn’t there, we need to create it. If **blocklist.txt** isn’t there, go ahead and click on **New File** in the upper right corner.
![New File](../images/new-file.png)

3. Paste the Klei ID you have acquired through the **server_log.txt**.

4. Once done, click on **Create File** and type in the name **blocklist.txt**.  Exactly like that, it’s crucial.
![blocklist](../images/blocklist.png)

5. And press Create File again, Start/Restart your server and when the player connects, they will see this: ![Ban](../images/banned.png)