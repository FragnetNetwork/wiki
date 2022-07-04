If you would like to download mods to your server, you can follow next steps:

**Step 1:** Subscribe/download any mods from client side that you wish to add to the server
**Step 2:** You can close the game and navigate to the following directory: `C:\Users\yourUsername\Documents\My Games\ArmaReforger\addons\`
**Step 3:** You will find folders named by mod IDs and you will need to open **ServerData.json** inside each folder to find details like **"id"**, **"name"** and **"version"**. Example:
```json
{
   "id": "591AF5BDA9F7CE8B",
   "name": "Capture & Hold",
   "revision": {
      "version": "1.0.0",
      "dependencies": [],
      "scenarios": [],
      "downloaded": true
   }
}
```
**Step 4:** Login to your account on [Fragify panel](https://panel.fragify.net/) and select your Arma Reforger server

**Step 5:** Navigate to **File Manager** on the left-side menu

**Step 6:** There you will find **config.json** file, and you will need to click on it for editing

**Step 7:** You will find a line that says **"mods": []** where you can input **"modId"**, **"name"** and **"version"** the following way:
```json
"mods":[
   {
      "modId":"591AF5BDA9F7CE8B",
      "name":"Capture & Hold",
      "version":"1.0.0"
   },
   {
      "modId": "PD7EGSE9T3KBGBK8",
      "name": "name of mod",
      "version": "1.2.3"
   }
    ]
```
**Step 8:** Paste **modId**, **name** and **version** that you found in ServerData.json file
**Step 9:** Repeat 8th step for adding more mods. Ensure that each mod section **{}** is divided by **,**.
**Step 10:** After you have added all mods that you wish to be added on the server, don’t forget to click on **Save Content** button
All mods added to **config.json** file will be downloaded and start to run on the startup of Arma Reforger server.

If mod requires Scenario, you will need to also find **"gameId"** in ServerData.json which is located inside the mods folder in the following directory `C:\Users\yourUsername\Documents\My Games\ArmaReforger\addons\`
It will look approximately like this:
```json
{
   "id": "3CUU9KNFJ6AUNXZD",
   "name": "name of mod",
   "revision": {
      "version": "1.0.0",
      "dependencies": [],
      "scenarios": [
         {
            "name": "name of scenario",
            "gameId": "{FGWZH7WSY6F7P45J}Missions/MissionHeader_1.conf"
         }
      ],
      "downloaded": true
   }
}
```
In this case, you will need to copy value of gameId which is in the example **{FGWZH7WSY6F7P45J}Missions/MissionHeader_1.conf** and paste in **Scenario ID** which can be found on Fragify panel in **"Settings"** option.
Note that you need to restart server for the changes to be applied.

**MODS UPDATE**

If mod receives update, don't forget to change **version** in **config.json** file.