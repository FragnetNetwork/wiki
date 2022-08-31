
# How to ban/kick player

You can kick/ban players via the Fragify console simply by typing in the command and pressing **Enter/Return**.

![Console Window](../images/console-window.png)

For player to be kicked from the server:
```
kick playername 
```
For player to be banned from the server:
```
ban playername
```

# How to unban player

To unban a player, you will need to remove the player's name and IP from **banlist.txt**.
After the first player has been banned, the server will create a banlist.txt since it didn't exist before the first server ban.
To do that, navigate to your **File Manager**, and find the **banlist.txt** file. It should be located in the directory right after clicking on **File Manager**.

![File Manager](../images/file-manager.png)

![Banlist](../images/banlist.png)

Once found, open the **banlist.txt**, and find the player you have banned. Remove the player's name and their IP located right under their name.

![Content of Banlist](../images/content-banlist.png)

After you have removed both lines, press **Save Content** button located on the lower right side of the window and the player should be unbanned.