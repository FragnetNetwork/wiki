Often you will find that custom commandline is one of your best friends when it comes to DayZ server. It’s important to know how to correctly set it up and have full control of your server.  
Generally speaking, custom commandline is required when you need to specify the mod order manually as certain mod dependencies needs to be loaded first in order for mods to properly work and server to be able to start.  
To create a custom commandline in DayZ you will need to follow the next steps:

**Step 1:** Log in to your account on our [game panel](https://gamepanel.fragnet.net/) and find your service  
**Step 2:** Go to **Commandline Manager**  
**Step 3:** Press on **Custom Commandline** and hit **+New**  
**Step 4:** You will be displayed a list with a lot of checkboxes. First you will need to name your custom commandline, to do this next to **Description** write the name of your commandline (ex. DayZ custom commandline)  
**Step 5:** On to the checkboxes you will need the following checkboxes like shown on a screenshot

![](images/image-20220322-122211.png")

**Step 7:** Fill in the required details and once you are done, press **Save**  
**Step 8:** On the right side of the custom commandline you will see two buttons **Edit** and **Select**, press **Select** and the newly created custom commandline will be selected

When creating a custom commandline and placing the mod IDs, make sure they are correctly placed in the following format, otherwise the server will have issue starting.  
ModID1;ModID2;ModID3;…  
  
This goes for both the -servermod and -mod option.