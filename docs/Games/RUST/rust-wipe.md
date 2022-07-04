#How to wipe your RUST server and/or Player Data

It is recommended that Rust server owners reset their worlds every 30-days to help keep their server community active.  

By doing the following steps, you will **irreversibly** delete your world file and/or player data.  

There are 2 ways you can wipe data from your RUST server:

###1 Using Fragnet RUST Server Wiper
----------------------------------

*   Go to your RUST service on the Fragnet Game Panel
*   Navigate to Rust Server Wiper
*   Make sure to select the identity you specified in your commandline!! (by default it's fragnet)
*   Simply select things that you want to wipe
*   Once ready, press Execute and let it finish
*   Your server will restart and everything your selected will be wiped  
    

![Wipe1](../images/wipe1.png)

###2 Manual wipe
--------------

Manual wipe is done either via File Manager on our panel, or by using an FTP client.    
  
Navigate to your /server/your\_server\_identity folder (by default it's /server/fragnet).  
Your world and player data is stored here.

To delete the **player data only**, delete the player \*.db files . This includes blueprints, inventories, positions, etc.  
![Wipe2](../images/wipe2.png)

Simply delete every file that starts with player\_.db

To delete the **world data only**, delete the files ending with **.map** and **.sav**. If you're not using a custom map this will be the file labeled "proceduralmap".  
![Wipe3](../images/wipe3.png)  

  
If you want to completely wipe your server, you would simply need to delete all the files mentioned above.

By deleting these files, you will **irreversibly** delete your world file and/or player data. Be careful when proceeding with this!