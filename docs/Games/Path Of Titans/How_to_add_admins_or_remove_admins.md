You can add or remove admins by using the following steps:

**Step 1:** Login to your account on [Fragify panel](https://panel.fragify.net/) and select your Path of Titans server.

**Step 2:** Ensure that the server is stopped and navigate to **File Manager** on the left side menu. 

**Step 3:** Navigate to the following directory: `PathOfTitans/Saved/Config/LinuxServer` and you will need to click on **Game.ini** file to edit it.

**Step 4:** Add `[/Script/PathOfTitans.IGameSession]` Enter under it Alderon Games ID(AGID) and you can add one player per line. For removing admin, simply remove the line.
### Example of Game.ini
```
[/Script/PathOfTitans.IGameSession]
ServerAdmins=087-234-324
ServerAdmins=348-892-843
ServerAdmins=249-453-328
;comments can be made by including semi-colon in the beginning
```
**Step 5:** Click on **"Save Content"** button and start/restart server for the changes to be applied.