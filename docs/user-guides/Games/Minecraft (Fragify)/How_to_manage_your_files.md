We provide you with full access over your server files for most of the games through both the game panel's integrated file manager, and the File transfer protocol (FTP). The integrated file manager is a lightweight solution for simple tasks such as file and folder deletions/renames, light file uploads. FTP is more suited for heavier tasks such as large file uploads (both in size and number), moving files from one directory to another and such.

Managing your server files via File Manager
-------------------------------------------

In case you need to upload a mod, plugin or simply edit a config on your server, it can be easily done via File Manager on your Fragify panel.

Simply navigate to “File Manager” tab where you will see a full directory tree.

You will have an option to Upload, Delete, Edit and Archive the files. Everything that’s needed in order to configure your server is available.

Managing your server files via SFTP
-----------------------------------

### Connecting to your SFTP account

You can follow these steps to access and manage your server files using FTP :

1.  Download and install an FTP client, FileZilla is one of the most popular and feature-rich ones: [Download FileZilla](https://filezilla-project.org/download.php?type=client)
    
2.  Connect to your FTP account using the following details:  
    \- Host : SERVER ADDRESS which is located under the “Settings” tab  
      **Warning** : Do not include the port after the IP address (I.E sftp://odin.fragify.net instead of sftp://odin.fragify.net:2022)  
    \- Username : Username which is located under the “Settings” tab  
    \- Password : Your SFTP password is the same as the password you use to access the panel.  
    \- Port : 2022
    

Use those credentials to fill in the field in your FTP client then click on "quick connect"

![](https://fragnet.atlassian.net/wiki/download/thumbnails/214990859/Screenshot_60.png?version=1&modificationDate=1619473272423&cacheVersion=1&api=v2&width=680 "Knowledge base > How to manage your server files > Screenshot_60.png")

Be careful when you type this information as you may get a 5 minutes ban if you attempt to login with the wrong credentials repeatedly. In that situation, simply disconnect and wait 5 minutes before trying again

### Uploading and downloading files or folders

FTP is particularly useful for backing up your server files, or uploading plugins/worlds/settings onto your Once connected to your FTP account, server files will be listed on the right side of the screen, whilst your computer's files will be listed on the left side.  
You can upload, download, and move files from your computer to your server and vice versa, as well as within the server's folders.

Alternatively, you may right-click on the relevant file or folder and hit the "Download" or "Upload" button.

![](https://fragnet.atlassian.net/wiki/download/attachments/214990859/Screenshot_61.png?version=1&modificationDate=1619473746095&cacheVersion=1&api=v2 "Knowledge base > How to manage your server files > Screenshot_61.png")