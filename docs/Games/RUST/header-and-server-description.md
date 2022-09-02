# How to add header image and server description

Header Image
------------

It is possible to have a header image on your Rust server. The header image adds a nice touch to your server and is a great way to show what your server is about before someone joins.  
The header image of your server appears when you click on the server in the Rust server browser.

### Preparing the Image Header

For the image to be loaded in the header, few rules must be followed.

*   The image size must be **512x256** and **.png** or **.jpg** formats.

There are quite a few online tools that can be used in case you need to resize your image.  
We recommend using Picresize https://picresize.com/. Upload the image and proceed to edit it.  
Under Resize your picture, select **Custom Size...** and write the resolution mentioned above. Ensure that **Image File Format** is set to **PNG** or **JPG**. After all changes are made, click on **I'm done, resize my picture!** button.

![Picresize Instructions](../images/picresize-instructions.png)

*   The image must be uploaded to a public image-sharing website. We recommend using [Imgur](https://imgur.com/). You can upload an image by using the drag and drop function.

Once you upload the image, copy the Imgur image's link by right-clicking on the image and selecting the **Copy image address** option.

![Example Imgur](../images/example-imgur.png)

### Adding the Image Header to your server

*   Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Rust server.
*   Navigate to the **Configure** option on the left-side menu and look for the variable **Server Image**. Paste the link of your image uploaded to Imgur.

![Configure](../images/configure.png)

![Server Image](../images/server-image.png)

*   Restart the server so the changes can take effect.

You should be able to see your header image once you click on your server in the Rust Server browser!


Server Description
------------------

A server description is a text that will appear when potential players click on a Rust server in the in-game listings. You can use this text to describe your server and attract new players.

It can be used for various things but is most commonly used for:

*   Specific rules that players should be aware of
*   Mentioned plugin that modified game style, such as gathering rates
*   Contact information
*   Server Wipe date

### Adding a description to your RUST server

Just like the Header Image, the server description is also set via variables in **Configure** option on the left-side menu.

*   Login to the [Fragify panel](https://panel.fragify.net/auth/login) and select your Rust server.
*   Navigate to **Configure** option on the left-side menu and look for **Description** variable. You can type any information that you would like to appear in your server's description in-game. 

![Configure](../images/configure.png)

![Description](../images/description.png)

*   Restart the server so the changes can take effect.

### Formatting the text

**New Lines**

If you want the text to appear on different lines, you can add the characters **\\n** to create a new line directly below it. You don't need to add spaces around the **\\n**. They can be directly touching text on either side.