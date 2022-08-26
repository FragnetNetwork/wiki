# Enabling/Disabling voice communication
1. Navigate to your **File Manager**.
![File Manager](../images/file-manager.png)

2. Go to **tf => cfg => server.cfg** and open up the config.
Once there, go to an empty line and add
```
sv_voiceenable 0 or 1
```
>0 to disable voice comms

>1 to enable voice comms

 ![](../images/server-config.png)

# Enabling cross-team voice communication
Open the same config, find an empty line and add
```
sv_alltalk 1
```
![](../images/alltalk-server-config.png)
Once done, click on **Save Content** and Start/Restart your server, and you’re ready.