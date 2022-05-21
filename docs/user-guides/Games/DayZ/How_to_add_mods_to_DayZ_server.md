This will be a long in-depth guide that shows you how to correctly add mods to your server.  
Before you proceed following the next steps just in case something goes wrong it will be good if you have a backup. To create a backup you can use this article on our knowledge base: [How to create a backup for Dayz server](/wiki/spaces/KB/pages/402948112/How+to+make+a+backup+of+your+DayZ+server)

Great, now that you created a backup let’s focus on getting everything ready for mods. You will first need to follow again one of our guides on [how to create a custom commandline for DayZ server](/wiki/spaces/KB/pages/402948121/Create+a+custom+commandline+for+the+DayZ+server).

### How to install mods on your server

After you selected your custom commandline you will find three sections on your game panel that will help you move through mods. Three of the sections are **Steam Workshop, Steam Workshop (installed), Steam Workshop (updates)**. Each one of them is important when it comes to mods.

Follow the next step to install mods on your server:  
**Step 1:** To find mods you will need to go to **Steam Workshop** and in the **Search box** write the name of the mod.  
**Step 2:** After you find desired mod simply press **Install**.  
Proceed with these steps for all of the mods you want to install on your server.

Even if mods are installed on your server that doesn’t mean that they are enabled, they are just installed

### How to enable mods on your server

This is the most important part of this guide and this will require a lot of attention to get mods working, however, if you follow these steps correctly everything should work fine.

**Step 1:** Go to **Steam Workshop (installed)**  
**Step 2:** You will find here all of the mods you installed on your server, now for every mod you want to enable on the server you will go ahead and select **Details** so it opens in a new page  
**Step 3:** After you opened details for all of the mods you want to enable on the server you will need to make them in order.

This is a very important step, some of the mods require other mods to be enabled/loaded before the specific one. To know if certain mod requires other mod in order to work there will be a box on mod Steam page that will show needed mod in order for this one to work, like shown on the next screenshot.  
If there is no Required Items box on mod Steam page then they can be loaded without any other mods being required

![](https://fragnet.atlassian.net/wiki/download/attachments/402980902/image-20220322-125900.png?version=1&modificationDate=1647953942570&cacheVersion=1&api=v2 "Knowledge base > How to add mods to DayZ server > image-20220322-125900.png")

If you don’t have the mod named here installed you will first need to install it.  
**Step 4:** After you ordered them by tabs in the browser, you will now need to start adjusting command line  
**Step 5:** Go to previously created custom commandline **Commandline Manager → Custom Commandline** and press **Edit**.  
**Step 6:** In the mods input box you will need to write mod ID. To find mod ID simply press on the tab of already opened mod Steam page, select URL and the copy the number like shown on the screenshot

![](https://fragnet.atlassian.net/wiki/download/thumbnails/402980902/image-20220322-130721.png?version=1&modificationDate=1647954443125&cacheVersion=1&api=v2&width=340 "Knowledge base > How to add mods to DayZ server > image-20220322-130721.png")

Mods are listed in the commandline like shown here, always start with @ and end with ; except the last one  
@1559212036;@1590841260;@1646187754

**Step 7:** After you successfully written all of the mods in the command line press **Save** and restart the server  
**Step 8:** Mods should now run properly on the server