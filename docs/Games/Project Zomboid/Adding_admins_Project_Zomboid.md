In order to add an admin to your Project Zomboid server, you will need to edit the serverPZ.db.  
  
The server will look in your zomboid database folder (_/server/Zomboid/db_) for a database file (serverPZ.db) with username / passwords to authorize people trying to connect to your server.

Stop your server and download serverPZ.db to your PC.

Next, download this: [SQLite Admin](http://sqliteadmin.orbmu2k.de/) It's for editing file based sql (sqlite) databases.

Go into Tables, click whitelist, expand it out and click a random field (say id)

Then click the Edit Data tab, and you can put data in. All you need to do is to tick the “Admin” checkbox next to the players that you want to have admin rights.  
Close the database once you've made your changes, and it'll auto save.   
Upload the modified file onto the server to replace the existing one.

Start the server and the player should have admin privileges.