# How to add admins to your RUST server

Admin access on a Rust server allows a player to execute all Rust commands in-game. This is important since it gives you access to the commands for keeping your server clean from the players violating your rules, but to many other things such as teleporting, spawning items and more!

A full list of Rust server commands can be found [here](http://rust.wikia.com/wiki/Server_Commands).

## Adding admins via configuration file

There are two admin user roles on a Rust server:

*   **ownerid** - This Admin role gives access to all admin commands, including access to add other Rust admins.
*   **moderatorid** - This Admin role gives access to all admin commands, but does not allow the user to add other admins.

To add an admin via configuration file on your server follow these few steps:

*   Go to your RUST service on the Fragnet Game Panel
*   Navigate to Configuration files
*   Use the Text editor for users.cfg
*   In the **users.cfg** put the following line, on each separate line, for each user you would like to assign as a Rust admin:  
    ownerid steamid64 "optional username" "optional reason"  
    or  
    You can add users as Rust moderator in the same **users.cfg** file by replacing "**ownerid**" in the above command with "**moderatorid**" like this:  
    moderatorid steamid64 "optional username" "optional reason"
    
    Here is an example of how a **users.cfg** would look like with multiple users added:  
    ownerid 76812312312312311 "Fragnet" "Some reason"  
    ownerid 76812312312312312 "Fragnet2"   
    moderatorid 76812312312312313 "Fragnet3" "Great helper"  
    moderatorid 76812312312312314 "Fragnet4"  
      
    
*   After adding users to the "**users.cfg**" file, click "**Save**" and then restart your Rust server.

## Adding admins via RCON

Admins/moderators can also be added via RCON console.

*   Connect to your server
*   While remaining in-game, go to your RUST service on the Fragnet Game Panel
*   Navigate to Facepunch WebRCON
*   Login and go to console
*   Simply write the following commands if you want to add admin:  
    ownerid steamid64 "optional username" "optional reason"  
    server.writecfg  
    or  
    moderatorid steamid64 "optional username" "optional reason"  
    server.writecfg  
    In case you want to add a moderator,
*   After this is done, simply reconnect to the server and allow that role to apply.

Other 3rd party apps can be used to input the above commands for adding admins. We suggest using [RustAdmin](https://www.rustadmin.com/).  

The **users.cfg** file on your server may not update until your server has been stopped/restarted.

  

You have successfully added new admin/moderator to your RUST server and those users will now have access to admin commands in-game!
