#Installing Oxide plugins on the server

There are many oxide plugins that can be installed on the server and which can improve your gameplay experience. It's up to you to decide what will be on the server and how it will be configured.

#### Prerequisites for the Oxide Plugins:

*   **uMod/OxideMod**

Oxide mod must be installed on your server in order plugins to run.  
Simply navigate to Mod Manager on your Game Panel and install it with one click**!  
**

Make sure that server is stopped before installing uMod/OxideMod!

  

Preparing the plugins
---------------------

*   Locate and download the plugins you wish to install to your server from the official uMod website.   
    Plugins will be downloaded in .cs format.
*   Move all of those downloaded plugins to an empty folder on your computer, so it's easier to find them.

Installing plugins on the server
--------------------------------

Now when you have downloaded the plugins and prepared them, we need to upload them to the server.  
We have 2 methods that we can use for this: File Manager and FTP Client.

### Method #1 Installing plugins via File Manager

*   Go to your RUST service on the Fragnet Game Panel
*   Navigate to File Manager
*   You will now see your server files
*   Go to **oxide/plugins**
*   Simply press Upload button and select the files you want to upload.  
    Those would be the files in the folder you prepared previously (.cs files)
*   Allow those files to fully upload
*   Once those files are uploaded, simply restart your server
*   Your oxide plugins will now be loaded on the server!

### Method #2 Using an FTP Client

*   Connect to your server using FTP client (preferably FileZilla)
*   When connected you will see your server files
*   Navigate to **oxide/plugins**
*   Transfer your oxide plugins (.cs files) from your computer to the mentioned folder
*   Allow those files to fully upload
*   Once those files are uploaded, simply restart your server via Game Panel
*   Your oxide plugins will now be loaded on the server!

  

Your Oxide plugins will generate configuration files which you can edit.
You can access those files by using any of 2 methods mentioned above. Configs are located on the following location: **oxide/config**


You have successfully installed Oxide plugins to your Rust server!