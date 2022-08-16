In this game, a whitelist is called an **Allowlist** since it prioritizes players on the list and afterwards, allows other players who aren’t on the list to join.

First, we need to turn on the **Allowlist** and then add the players' Klei IDs to the list.

To enable the Allowlist you need to open the cluster.ini file.

1. Click on File Manager on your Fragify game panel and then go to `DoNotStarveTogether => config => server => cluster.ini`.

![File Manager](../images/file-manager.png)

2. Once you have opened the cluster.ini file navigate to the [NETWORK] section. And add this new line to it, and replace the word Number with the number you want the reserved slots to be
```
whitelist_slots = number
``` 
In this example, I have used the number 5, and it should look something like this:
![Example Whitelist](../images/example-whitelist.png)

Now that we have activated the whitelist option we need to create a whitelist.txt file containing the Klei IDs of all the players that will have a reserved slot.

3. Lets get to creating a whitelist, go to `DoNotStarveTogether  => config => server`.

4. Once there, click on the **New File** button located in the upper right corner.
![New File](../images/new-file.png)

5. Afterwards, insert the Klei IDs of the players that need the whitelist and then click on **Create File**. 
![Example Whitelist](../images/whitelist-txt.png)
It will prompt you for a name. It needs to be named **whitelist.txt** and click again on **Create File**.
![whitelist.txt](../images/create-whitelist.png)

Done! Don't forget to Start/Restart your server. The players located in the whitelist will have priority to other players connecting.