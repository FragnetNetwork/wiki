# How to wipe your Rust server and/or Player Data

It is recommended that Rust server owners reset their worlds every 30-days to help keep their server community active.  

By doing the following steps, you will **irreversibly** delete your world file and/or player data.  

There are 2 ways you can wipe data from your Rust server:

# #1 Using Fragify Wipe function
----------------------------------

*   Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Rust server.

*   Navigate to **Manage Wipes** function on the left-side menu.

![Manage Wipes](../images/manage-wipes.png)

*   Set the **name**, **description**, **map size** and **map seed** to your preferences or set to 0/empty to be left unchanged. 
> If you wish to set random seed on every wipe, click on **Random Seed** to be enabled.

![Example of Wipe Options](../images/example-wipeoptions.png)

*   If you want to remove specific files, you can input the exact path and name of the file and click on **Add** button. 

* You can also choose to **Wipe Blueprints**, **Wipe World**, **Restart Server** after wipe, **Schedule Wipe** for custom time and date. 

*   Once ready, press **Wipe** button.

![Example of Wipe Options](../images/example-wipeoptions1.png)

*   Your server will restart and everything your selected will be wiped  

# #2 Manual wipe
--------------

Manual wipe is done either via File Manager on our Fragify panel.    
  
Navigate to your `/server/yourServerIdentity` folder (by default it's `/server/rust`).  
Your world and player data is stored here.

To delete the **player data only**, delete the player **\*.db** files . This includes blueprints, inventories, positions, etc.  

Simply delete every file that starts with **player\_.db**.

To delete the **world data only**, delete the files ending with **.map** and **.sav**. If you're not using a custom map this will be the file labeled "proceduralmap".   

If you want to completely wipe your server, you would simply need to delete all the files mentioned above.

By deleting these files, you will **irreversibly** delete your world file and/or player data. Be careful when proceeding with this!