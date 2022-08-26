You will need sourcemod installed to be able to follow the guide.
If you're having any issues finding out how to install it, please follow our guide on how to install sourcemod [here](How_to_install_metamod_and_sourcemod_on_your_TF2_server.md).

1. Firstly navigate to your **File Manager**.
![File Manager](../images/file-manager.png)

2. Go to **tf => addons => sourcemod => configs => admins.cfg** file. Scroll down to the end of the script until you encounter:
```
Admins
{
}
```
Now you have to input your info in this format:
```
  "PlayerNickname" 
  { 
   "auth"  "steam" 
   "identity"  "insert_players_steamID" 
    "flags"  "z" 
 "immunity"  "99" 
  }
```
In the end it should look something like this:
```
Admins
{
  "PlayerNickname" 
  { 
   "auth"  "steam" 
   "identity"  "insert_players_steamID" 
    "flags"  "z" 
 "immunity"  "99" 
  }
}
```
![](../images/example-admin.png)
Once done, click on **Save Content** and Start/Restart your server.