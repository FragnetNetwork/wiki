By default, a new world is generated the first time a Minecraft server is started.  
If you wish to upload an existing world to your server, follow these steps:

1.  Log in to our Game Panel ([gamepanel.fragnet.net](https://gamepanel.fragnet.net/))
    
2.  Click on Game Services > Your Minecraft server
    
3.  Stop your server (preferably using McMyAdmin, as it will gracefully shut down your server)
    
4.  Click on File Manager. (You can also do this via FTP)
    
5.  Upload your world, preferably in a .zip format, to the ROOT folder. The Single Player world should be located in: C:\\documents and settings\\USERNAME\\application data\\.Minecrate\\saves or C:\\Users\\USERNAME\\AppData\\Roaming\\.minecraft\\saves
    
6.  If you already have a folder name matching your uploaded world, rename or delete it. Another option is to edit level-name in server.properties, which points out the world folder to load. You can edit server.properties in our Game Panel, by clicking Configuration Files > Text Editor for server.properties.
    
7.  Unzip your uploaded world (using the drop-down-menu to the right of the file name)
    
8.  Once unzipped, start your server and you are done!