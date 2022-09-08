The in-game console can be accessed by pressing the **Tilde (`)** key.

Pressing it once will open a small command line window at the bottom of the screen: 

![Console](../images/console.png)

Pressing it twice will open a large window with a command line and logs located on the screen: 

![Large Console](../images/large-console.png)

You can check the full list of Satisfactory commands here: https://satisfactory.fandom.com/wiki/Console

If by any chance you are unable to turn on the console.
You can turn it on with these steps:

1\. Close your Satisfactory game.

2\. Press **WINDOWS + R** to open the RUN window, and paste this line in there `%LOCALAPPDATA%\FactoryGame\Saved\Config\WindowsNoEditor`.

3\. A window filled with ini files should popup. Find the file called **Input.ini**.

4\. Add these 2 lines to the bottom of the ini file:
```
[/script/engine.inputsettings]
ConsoleKey=P
```
The console key can be changed to any button you wish.

Launch your game, use the button you have configured, and it should work.