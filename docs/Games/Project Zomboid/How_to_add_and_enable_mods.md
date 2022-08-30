Adding mods to your Project Zomboid server should be easy. Just follow these steps.

1. Go to [Steam Workshop page of Project Zomboid](https://steamcommunity.com/app/108600/workshop) and subscribe to the mods that you would like to play with.

2. Once you subscribed to mods, go to their individual pages and look for **Workshop ID** and **Mod ID** in their descriptions that are usually located at the bottom. Those IDs will be required for the mods to be downloaded on the server and enabled.
Please note that some mods will have other mods as requirements which you can find in **Required Items** field.

![Workshop Mod](../images/workshop-mod.png)
![Required Itens](../images/required-items.png)

3. Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Project Zomboid server.
    
4. Navigate to **Configure** option on the left-side menu and look for **Mod Names** and **Mod Workshop ID's** variables.

![Configure](../images/configure.png)
![Mod Variables](../images/mod-variables.png)

5. Paste **Workshop ID** to the **Mod Workshop ID's** field and **Mod ID** to the **Mod Names** field.
Example:

![Example](../images/example-mods.png)

If you want to download and enable multiple mods, you will need to separate them with semi-colon (`;`). Example:

![Example](../images/example-multiple-mods.png)

6.  Start/Restart your server and mods should be loaded on your server.