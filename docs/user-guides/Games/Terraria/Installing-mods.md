#Adding Mods

### Installing tModLoader

In order to install any mod to your Terraria server, tModLoader needs to be installed.

This can be done via your control-panel, simply navigate to your Terraria Game Panel and open the "**Mod Manager**". Once opened install the "tModLoader" mod which you can find there.

### Installing Mods

You now have the modding platform tModLoader installed on your server, that means we can start installing Terraria mods. These can be found and downloaded at different locations across the internet, but most common is the Terraria [official forums](https://forums.terraria.org/index.php?forums/client-server-mods-tools.116/). Find the mods you want to have on your server and download them to your local PC.

Now that you have the mods on your PC, you will need to upload them to your server. There are two ways to do this, either via FTP connection or via the file-manager in your control-panel. For the sake of simplicity, we'll go with the file-manager as it requires no third party programs (granted, you can use the Windows file explorer for FTP as well).

Open your game panel again, and find "**File Manager**", open it up and you'll see a "**Mods**" folder (this will only show up if you have installed tModLoader as explained earlier in this post). Click on the aforementioned "**Mods**" folder and click the "**Upload**" button, go ahead and click "**Select Files**" to find the mod-files you downloaded earlier, they will have the extension "tmod". Once selected, click "Upload" and the files will be automatically uploaded to your "**Mods**" folder.  
  
When the files are in the correct folder, go back into your game panel and find "**Configuration files**", click it and you'll find a file called "Mods\\enabled.json" in the bottom. Edit this by clicking on the "Text editor" button. It will look like this:

\[
"Mod1",
"Mod2"
\]

What this file does is enable your mods, they will not be automatically enabled after uploading them, so you'll have to enable them yourselves by typing in their names. For example, let's say I've uploaded the Tremor mod and the Calamity mod to my server, I would need to update the file to say:

\[
"Tremor",
"Calamity"
\]

If I only uploaded the Tremor mod, It would look like this (notice that I removed the comma-sign after the first mod, as this is only to be used when there are more than one mod):

\[
"Tremor"
\]

If you have more than two mods, you will need to add commas after each one that is followed by another, in other words no comma on the last mod you load. When you've edited the file, save it and start your server up, the mods should now be loading correctly.

  

If you have any questions in regards to this, feel free to submit a support ticket and our support-team will be happy to assist you.