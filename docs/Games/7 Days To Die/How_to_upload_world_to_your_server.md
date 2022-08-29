
1. You will need to navigate to your World folder. It is usually saved in the following directory: `C:\Users\YourPCUsername\AppData\Roaming\7 Days to Die\Saves\NameOfYourWorld`
![World](../images/world.png)

2. After finding the world you want to upload, you need to make a `.zip` archive of the world folder inside **Saves** .
> If the world is randomly generated, you will need also include **GeneratedWorlds** folder that can be found in the following path: `C:\Users\YourPCUsername\AppData\Roaming\7 Days to Die\`
![Saves](../images/saves.png)
![GeneratedWorlds](../images/generated-worlds.png)

3. Login to your [Fragify Panel](https://panel.fragify.net/auth/login) and select your 7 Days To Die server.

4. Navigate to **File Manager** on the left-side menu and go to `.local/share/7DaysToDie/`.
![File Manager](../images/file-manager.png)
![Example World](../images/example-world.png)

5. You will need to drag and drop your zip archive with the world folder in `.local/share/7DaysToDie/Saves`.
![Example Saves](../images/example-saves.png)
 While world zip archive from **GeneratedWorlds** will have to be unarchived in `.local/share/7DaysToDie/GeneratedWorlds`.
 ![Example GeneratedWorlds](../images/example-generatedworlds.png)

6. You will need to go to **Configure** on the left-side menu and look for the **Game World** and **Game Name** variables. Set them to the name of the world folders that you have uploaded. 
![Example Game World](../images/example-gameworld.png)

7. Restart the server, and it is ready!