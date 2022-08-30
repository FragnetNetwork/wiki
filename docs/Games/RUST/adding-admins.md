# How to add admins to your RUST server

Admin access on a Rust server allows a player to execute all Rust commands in-game. This is important since it gives you access to the commands for keeping your server clean from the players violating your rules, but to many other things such as teleporting, spawning items and more!

A full list of Rust server commands can be found [here](http://rust.wikia.com/wiki/Server_Commands).

## Adding admins via a configuration file

There are two admin user roles on a Rust server:

*   **ownerid** - This Admin role gives access to all admin commands, including access to add other Rust admins.
*   **moderatorid** - This Admin role gives access to all admin commands but does not allow the user to add other admins.

To add an admin via configuration file on your server, follow these few steps:

*   Go to your Rust server on the Fragify Game Panel
*   Navigate to **File Manager** on the left-side menu.

![File Manager](../images/file-manager.png)

*   Go to the following directory `server/rust/cfg/` and you will find there **users.cfg** file.
>If you use custom server identity, the location of **users.cfg** file will be in `server\nameOfYourServerIdentity\cfg\`

*  Open **users.cfg** and input the following line, on each separate line, for each user you would like to assign as a Rust admin:  
```
ownerid Steam64ID "optional username" "optional reason"
```
You can add users as Rust moderator in the same **users.cfg** file by replacing "**ownerid**" in the above command with "**moderatorid**" like this:

```  
moderatorid steamid64 "optional username" "optional reason"
```

Here is an example of how a **users.cfg** would look like with multiple users added:  

```
ownerid 76812312312312311 "Fragnet" "Some reason"  
ownerid 76812312312312312 "Fragnet2"   
moderatorid 76812312312312313 "Fragnet3" "Great helper"  
moderatorid 76812312312312314 "Fragnet4"  
```      
    
*   After adding users to the "**users.cfg**" file, click "**Save Content**" and then restart your Rust server for the changes to be applied.

## Adding admins via RCON

Admins/moderators can also be added via the RCON console.

*   Connect to your server

*   While remaining in-game, go to your Rust server on the Fragify Game Panel

*   You will see server's console and **Type a command...** input window. 

*   Simply write the following commands if you want to add admin: 
``` 
ownerid steamid64 "optional username" "optional reason"  
server.writecfg
```

In case you want to add a moderator:
```
moderatorid steamid64 "optional username" "optional reason"  
server.writecfg 
``` 
*   After this is done, simply reconnect to the server and allow that role to apply.

Other 3rd party apps can be used to input the above commands for adding admins. We suggest using [RustAdmin](https://www.rustadmin.com/).  

The **users.cfg** file on your server may not update until your server has been stopped/restarted.

You have successfully added a new admin/moderator to your Rust server, and those users will now have access to admin commands in-game!
