For example, a server link on an Unturned server can be used to redirect people to a voice server or any websites associated with your server (clan site, group site etc.).

1. Navigate to your **File Manager**. 

![File Manager](../images/file-manager.png)

2. Go to `Servers => Default => Config.json` and open up the config.

3. Once there at the beginning, you will find the command called `Links`. 
![Links](../images/links.png)

Instead of null, you need to add:
```
[
 {
"Message": "Name_of_the_website",
"URL": "https://example.com"
 },
 {
"Message": "Discord Server",
"URL": "https://discord_url"
 }
]
```
![](../images/example-links.png)
You can add more after the ` },` in the code above
if you have more links to connect to:
```
{
"Message": "Name_regarding_the_link",
"URL": "https://url.com"
},
```
>Note that last part should finish with dot `}.` instead of coma `},`.

4. Click on **Save Content**, and you’re good to go.
Start/Restart your server and check the links out when connecting to the server.