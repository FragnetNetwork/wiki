1. Make sure that your server is on `tModLoader` template. You can check it in **Templates** option on the left-side menu. 

![Templates](../images/templates.png)

2. Install tModLoader client from Steam: https://store.steampowered.com/app/1281930/tModLoader/

> More information about client-side installation can be found [here](https://github.com/tModLoader/tModLoader/wiki/tModLoader-guide-for-players).

3. Once installed tModLoader, you can go to **Workshop** => **Download Mods** option in menu to see list of mods that can be installed. Install mods that you would like to play with.

![Workshop](../images/workshop.png)

![Download Mods](../images/download-mods.png)

4. After downloading mods, go to **Manage Mods** option in the main menu in-game. Enable mods that you have installed.

![Manage Mods](../images/manage-mods.png) 

![Enable Mods](../images/enable-all.png)

All mods should be set to **Enabled** status as shown on the screenshot above. 

5. Navigate to **Open Mods Folder** option on the bottom. The new explorer window will open with `enabled.json` file and window with list of tModLoader mods from Steam Workshop. 

![Open Mods Folder](../images/open-mods-folder.png)

6. Go to Fragify Panel and select **File Manager** option on the left-side menu. Navigate to `mods` folder. 

![File Manager](../images/file-manager.png)

7. We will need to get `enabled.json` file from one of the opened folders on the path: `C:\Users\yourPCUsername\Documents\My Games\Terraria\tModLoader\Mods` and upload it `mods` folder on the server by clicking on **Upload** button or using the drag and drop function. The same should be done for another folder that was opened with tModLoader mods.

![Upload](../images/upload.png)

![tModLoader Mods Location](../images/tmodloader-mods.gif)

> As you can see on the gif above, all mods will be in their own folders. You will need to open each folder and upload `.tmod` file to `mods` folder. If you have downloaded several version of mods, you will need to select the latest. Folder format of mods goes like this: `[year].[highest number]`. The latest version would be like `2022.8`

8. Restart the server and all mods should be enabled on your server. 