There are 4 difficulties that Terraria offers: Journey, Classic, Mediumcore, Hardcore. You can read more information about them [here](https://terraria.fandom.com/wiki/Difficulty).

# Change difficulty of a new world

1\. Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Terraria server.

2\. Stop the server and go to **Configure** option on the left-side menu.

![Configure](../images/configure.png)

3\. Find **Difficulty** variable and set it to the desired number of difficulty in which 0 = `normal`, 1 = `expert`, 2 = `master`, 3 = `journey`. Note that for `journey` difficulty, you will need to create a `journey` character in game. 

4\. Once done, start/restart the server and the world will run on the choosen difficulty. 

# Change difficulty of an existing world

1\. Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Terraria server.

2\. Stop the server and go to **File Manager**. Navigate to `saves/Worlds` directory where you will find `theNameOfYourWorld.wld` world file. 

3\. Click on **...** and select **Download** option on the menu. 

![World File Download](../images/world-file.png)

4\. Once you have acquired the world file on your PC, you will need to download the Terraria Map Editor/TEdit from [here](https://github.com/TEdit/Terraria-Map-Editor/releases/).

5\. Make a backup of your world for safety and open your world file in TEdit.

6\. Once the map has been opened, click on **World Properties** and find the option called **Game Mode**. Change it to the difficulty you want and save it by clicking **File** => **Save**.

![TEdit](../images/tedit.png)

7\. Now since the difficulty has been changed, all we need to do is upload the world to the same directory. Return to your **File Manager** and go to `saves/Worlds`. Click on **Upload** button or use the drag and drop function. 

8\. Start your server and it should load the world you have changed the difficulty on.

# Change difficulty of a TShock world

1\. First, you will need to become an admin on your TShock server. You can read about it [here](How_to_become_an_admin_on_TShock_server.md).

2\. Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Terraria TShock server.

3\. Input in Console's input window with `Type a command..` one of the following commands that will change the difficulty of your world:

```
/gamemode Normal
/gamemode Expert
/gamemode Master
/gamemode Journey
```
