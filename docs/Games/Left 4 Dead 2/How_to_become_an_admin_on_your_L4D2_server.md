1. Firstly, navigate to your **File Manager**. 

![File Manager](../images/file-manager.png)

2. Then go to `left4dead2 => addons => sourcemod => configs => admins.cfg`.

3. Scroll down to the end of the script until you find:
```
Admins
{

}
```

4. Now you need to input your info in this format:

  "PlayerNickname" 
  { 

   "auth"  "steam" 

   "identity"  "insert_players_steamID" 

    "flags"  "z" 

    "immunity"  "99" 

  }

In the end, it should look something like this:
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

![Example Admin](../images/example-admin.png)

5. Once done, click on **Save Content** and Start/Restart your server.