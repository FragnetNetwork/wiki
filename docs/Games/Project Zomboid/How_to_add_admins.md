Adding mods to your Project Zomboid server should be easy. Just follow these steps.

1.  On the game panel navigate to “Configuration Files” and edit _server\\Zomboid\\Server\\serverPZ.ini_
    
2.  Locate the “WorkshopItems=” line and add the Steam Workshop ID (found at the end of the URL of the mod's Steam Workshop) in a semi-colon ; separated string.  
    Example  
      
    ”_WorkshopItems=1234567890;1234567890”_  
    
3.  In the same file, find the following line: “Mods=”
    
4.  The value needed for this section can often be found in the description of the mod on the Steam Workshop page.  
    Example  
      
    ”_Workshop ID: 123456789_  
    _Mod ID: ModName1”_  
    
    Once you have that value you can insert it like this:  
      
    _”Mods=ModName1;ModName2”_  
    
5.  Save the file and restart your server.
    

  
The mods should now be activated on your server.