#Adding Administrators

After installing TShock from the Mod Manager, start or restart the server and open the "Web Console" in your control-panel. When the server is finished loading, you will see a message such as the following:

  

TShock Notice: To become SuperAdmin, join the game and type /auth 6969004, _your auth code will be different, this is used as an example._

To become superadmin, join the game and type**:**

**/auth \[authcode\]**

So if your authcode is 6969004 you would type:

**/auth 6969004**

By becoming a super admin, you gain the ability to create a user account on the server, giving you access to all commands.

*   Next, enter:  **/user add \[username\] \[password\]** **superadmin**  
    Example: /user add fragnet qwerty superadmin
*   Log in with the superadmin user you just created by entering: **/login \[username\] \[password\]  
    **Example: /login fragnet qwerty

### Adding Users/Admins

To add a new user or admin, enter the following: **/user add \[username\] \[password\] \[group\]**

*   Example #1 (Add a VIP user): **/user add sarah connor vip**
*   Example #2 (Add another Admin): **/user add sarah connor newadmin**

Alternatively, if the user you wish to add has already registered (using /register \[username\] \[password\]) you may also edit that user's usergroup by editing the **tshock\\tshock.sqlite** database-file (Users.Usergroup - see below). _Users who have their access added or changed need only re-join the server for their permissions to take effect._

tshock.sqlite can be edited with the following tool: [Link to download page](http://sqliteadmin.orbmu2k.de/) | [Direct download](http://download.orbmu2k.de/download.php?id=19)