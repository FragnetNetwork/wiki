There are two ways to add bots to your server, via the server.cfg or via console commands
In this guide, we'll explain both methods.
# Adding Bots via the server.cfg
1. Navigate to your File Manage and go to **tf => cfg** directory.
![](../images/file-manager.png) 
2. Open up the **server.cfg** and we will need to add these lines:
```
tf_bot_quota "number" Choose any number you want
tf_bot_auto_vacate "1"
tf_bot_quota_mode "fill"
```
It should look something like this:
![](../images/example-bots.png)
3. Once done, click on **Save Content** and **Start** the server, and the server should be filled with the chosen amount of bots.

# Adding bots via console commands
1. Go to your Fragify console and type in this command
```
tf_bot_add number team class
```
>Replace the **number** with any you want [1,2,3,4,5].

>Replace **team** with either **red** or **blue**.

> Replace class with any of the classes in the game: **scout, soldier, pyro, demoman, heavyweapons, engineer, medic, sniper** or **spy**.

Example command: ```tf_bot_add 2 red soldier```
And it should look like this:
![](../mages/example-command.png)

# Kicking bots from your server

Use the command `tf_bot_kick name`
An example would be: `tf_bot_kick Red_Lynx`
> If you wish to kick all bots, use the command `tf_bot_kick all`.