This will be a guide on how you can add admin to your [7 Days To Die](https://fragnet.net/games/7d2d) server.

### **Adding admin through the config file**

**Step 1:** Log in to your account on our [Fragify panel](https://panel.fragify.net/auth/login) and find your 7 Days To Die server.

**Step 2:** Before you do any changes, you will first need to stop your server.  

**Step 3:** Click on a section named **File Manager** on the left-side menu.

![File Manager](../images/file-manager.png)  

**Step 4:** Navigate to the following directory: `.local/share/7DaysToDie/Saves` and open **serveradmin.xml** file. 

**Step 5:** You will need a third party program, so you can find Steam64 ID. One of the most famous sites is [https://steamid.xyz/](https://steamid.xyz/). Enter the Steam Profile URL of the person you want to add as admin and copy the Steam64 ID.  

**Step 6:** Go back to the config file and search for section:
```
<admins>
</admins>
```
Insert the following line:
```
<!-- <admin steamID="yourSteam64ID" permission_level="0" /> -->
``` 
between `<admins>` and `</admins>` and paste your Steam64 ID in `steamID=`.
Example:
```
<admins>
    <user steamID="76561198021925107" permission_level="0" />
</admins>
```
**Step 7:** Start the server.