#How to manage your server files using FTP (File transfer protocol)

We provide you with full access over your server files for most of the games through both the game panel's integrated file manager, and the File transfer protocol (FTP). The integrated file manager is a lightweight solution for simple tasks such as file and folder deletions/renames, light file uploads. FTP is more suited for heavier tasks such as large file uploads (both in size and number), moving files from one directory to another and such.

While we provide full access over server files for majority games that we are hosting, there are some games that are either limited or completely inaccessible via FTP or File Manager as per developer demands.

Connecting to your FTP Account
==============================

You can follow these steps to access and manage your server files using FTP :

1.  Download and install an FTP client, FileZilla is one of the most popular and feature-rich ones: [Download FileZilla](https://filezilla-project.org/download.php?type=client)
2.  Connect to your FTP account using the following details:  
    \- Host : Your game server address  
      **Warning** : Do not include the port after the IP address (I.E 192.168.1.1 instead of 192.168.1.1:25565)  
    \- Username : Your game panel username  
    \- Password : Your game panel password  
    \- Port : 8821 

Use those credentials to fill in the field in your FTP client then click on "quick connect"

![FTP1](../images/FTP1.png)

Be careful when you type this information as you may get a 5 minutes ban if you attempt to login with the wrong credentials repeatedly. In that situation, simply disconnect and wait 5 minutes before trying again

Uploading and downloading files or folders
==========================================
 

FTP is particularly useful for backing up your server files, or uploading plugins/worlds/settings onto your server.  
  
Once connected to your FTP account, server files will be listed on the right side of the screen, whilst your computer's files will be listed on the left side.  
You can upload, download, and move files from your computer to your server and vice versa, as well as within the server's folders.  
  
Alternatively, you may right click on the relevant file or folder and hit the "Download" or "Upload" button.