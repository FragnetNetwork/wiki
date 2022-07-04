#How to add header image and server description

Header Image
------------

It is possible to have a header image on your RUST server. The header image adds a nice touch to your server and is a great way to show what your server is about before someone joins.  
Header image of your server appear when you click on the server in the RUST server browser.

### Preparing the Image Header

In order for the image to be loaded in the header, there are few rules that need to be followed.

*   The image size must be 512x256
*   The image must be uploaded to a public image sharing website. We recommend using Imgur.

Once you upload the image, copy the Imgur image’s link.

There are quite a few online tools that can be used in case you need to resize your image.  
We recommend using Picresize. Simply upload the image and proceed to editing it.  
Under the Resize your picture, select custom size and write the resolution mentioned above.

### Adding the Image Header to your server

*   Go to your RUST service on the Fragnet Game Panel
*   Navigate to Commandline Manager -> Custom commandline
*   Edit your existing Custom commandline or create a new one
*   Under the -server.headerimage parameter paste your image link  
    Example: [https://i.imgur.com/unknwn](https://i.imgur.com/unknwn)
*   Add the .jpg extension at the end of your link  
    Example: [https://i.imgur.com/unknwn.jpg](https://i.imgur.com/unknwn.jpg)
*   Once done, tick the checkbox before the -server.headerimage parameter and press Save.
*   Restart the server so the changes can take effect.

You should be able to see your header image once you click on your server in the RUST Server browser!

  

Server Description
------------------

A server description is text that will appear when potential players click on a Rust server in the in-game listings. You can use this text to describe your server and attract new players.

It can be used for various things but most commonly used for:

*   Specific rules that players should be aware of
*   Mentioned plugin that modified game style, such as gathering rates
*   Contact information
*   Server Wipe date

### Adding a description to your RUST server

Just like the Header Image, server description is also set via Custom Commandline

*   Go to your RUST service on the Fragnet Game Panel
*   Navigate to Commandline Manager -> Custom commandline
*   Edit your existing Custom commandline or create a new one
*   Under the -server.description parameter write the text you want to have
*   Once done, tick the checkbox before the -server.description parameter and press Save
*   Restart the server so the changes can take effect.

### Formatting the text

**New Lines**

If you want text to appear on different lines, you can add the characters \\n to create a new line directly below it. You don't need to add spaces around the \\n, they can be directly touching text on either side.

For example, adding the text below to the server.description parameter…

Testing...\\nStill testing...\\nHosted by Fragnet.net

…will create the following description for the server, when viewed in the in-game listings:

![Header](../images/serverinfo.png)