The process for running mods outside single player is very crude and manual right now. The developers will make the process simpler in the future and hopefully add support for automatic download of mods when you join a server.

The process for running mods outside single player is very crude and manual right now. The developers will make the process simpler in the future and hopefully add support for automatic download of mods when you join a server.

### Installing Mods on your client

The fastest and easiest way to get the mod information is to subscribe to them on Steam. This will cause the client to begin downloading and installing the selected mods automatically to the single player installation on your local computer. This has the side effect of getting all the mods set up on your client anyway, which you will need to connect to the server later on.

Once it's done downloading them, you need to find where the file are stored on your computer. They will most frequently be found at `/ProgramFiles(x86)/Steam/steamapps/workshop/content/440900` unless you installed your steam somewhere else.

`440900` is the ID number for the game Conan Exiles on Steam. Each folder inside will be the workshop ID number of a mod downloaded from the steam workshop. Inside those folders you will find the actual mod files, all ending in `.pak`; those are the files you will need to copy, the numbered folders are not needed, just the files inside the folder.

### Create a “Mods” folder on the server

In the `/ConanSandbox` directory of your Conan Exiles server, create a folder titled `Mods`.

### Upload the mods to your server

Once you have all the `.pak` files, we recommend "zipping" the files using any of the tools that provide such option (7zip, WinRAR etc.), and upload them to the `/Mods` folder on your server.

Once they're uploaded to the `/Mods` folder, unzip the zip file you created.

You can use drag and drop in the file manager tab of your control panel, or FTP software. For any larger zips files, we recommend using FTP, as uploads can be resumable in-case of any network problems.

Otherwise, you can upload the mod files one by one.

### Creating modlist.txt config file

To actually enable the mods on your server, you need to edit a text file which will contain the file names of each mod that needs to be loaded on the server.  
The contents of the file should look like this, where each mod needs to have an asterisk in front of it and each mod should be in a separate line, like

\*ModName1.pak
\*ModName2.pak

Once you have completed everything, restart your server.  
On the next restart, the server should load all the mods you have listed in the `modlist.txt` file and your server will be running with mods now!