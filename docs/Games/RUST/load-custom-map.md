# How to load the custom map on your Rust Server

It is possible to have a custom map on the Rust Server apart from the original ones, and it's relatively easy to load one. You can get custom maps from http://playrust.io/
or https://rustmaps.com/.

Just follow these simple steps:

1\.  Upload your custom .map file to Dropbox.

2\.  Once uploaded, copy the download link.

3\.  Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Rust server.

4\.  Navigate to the **Configure** option on the left-side menu and look for **Server Level URL** variable.

![Configure](../images/configure.png)

![Server Level URL](../images/server-lvl-url.png)

5\.  Paste the download link. Example:
``` 
 https://www.dropbox.com/s/<randomcharacters>/<mapname>.map?dl=0
```
6\.  Change the **dl=0** to **dl=1** in that link.  Example: 
```
https://www.dropbox.com/s/<randomcharacters>/<mapname>.map?dl=1
```
7\.  Once done, restart the server so the changes can take effect.

You have now successfully added a custom map to your Rust server!