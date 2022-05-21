Adding yourself as an administrator in SourceMod is actually easier than you would think.  
  
1\. Write down your SteamID, you will be needing this later. ([How do I find my Steam ID?](https://wiki.fragnet.net/pages/viewpage.action?pageId=66299))  
2. [Access the Game Panel](https://gamepanel.fragnet.net/Interface/Base/Login.aspx), and authenticate using your set or provided log-in details.  
3\. Go to your CS:GO server.  
4\. Click on File Manager then go to File Manager -> csgo -> addons -> sourcemod -> configs and then next to admins\_simple.ini in the drop down menu, choose edit.  
5\. Scroll down to the bottom and then you write this "STEAM\_1:X:XXXXXX" "99:z" (replacing the SteamID with your steam id).  
6\. Hit save and then restart your server.  
  
If you have followed the steps above, the highest amount of privileges (99 immunity, Z - root flag) should have been assigned to your account. To verify that access has been given, connect to your server, open your console and execute the "sm\_admin" command or the "!admin" trigger in chat, without the quotes.  
The result should be a menu on the left side of your screen. If the permissions have not been added or the game server has not been restarted, you might receive an error message, as you might not have enough permission.  
  
If you encounter any problems or have questions concerning this topic, please do not hesitate to inquiry us through creating a ticket.