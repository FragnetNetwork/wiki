If you would like a private server where people need a valid user/pass to join, creating a whitelist is necessary.

This is a bit more of a mess on than it will be down the line, but once you're set up its pretty easy to manage.

The server will look in your zomboid database folder (_/server/Zomboid/db_) for a database file (serverPZ.db) with username / passwords to authorize people trying to connect to your server.

Stop your server and download serverPZ.db to your PC.

Next, download this: [SQLite Admin](http://sqliteadmin.orbmu2k.de/) It's for editing file based sql (sqlite) databases.

Go into Tables, click whitelist, expand it out and click a random field (say id)

Then click the Edit Data tab, and you can put data in. All you need to do to add a user is click the + icon, and then (in order) put **serverPZ** into the 'world' column, then add a username and password into their respective columns. Close the database once you've made your changes and it'll auto save.   
Upload the modified file onto the server to replace the existing one

Now edit the server configuration and set "Open" setting to "false". Save

Start server.