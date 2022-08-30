# Getting the map ID
Browse the Steam Workshop and choose a map that you would like to play on [here](https://steamcommunity.com/app/440/workshop/).
And copy the map ID located in the link on the workshop page:
![Workshop Link](../images/workshop-link.png)

# Creating a map cycle
1. Go to File manager and navigate to **tf => cfg** directory. Click on New File on the window's upper right side.
![New File](../images/new-file.png)

2. We need to create a **mapcycle.txt** file to give the server a list of maps to load.
After clicking on **New File**, you will need to name it:
`mapcycle.txt`.
>If you already have one with the same name, you can name it by adding a prefix to the name, for instance `examplemapcycle.txt`. Click on Create File once again.
You’ve successfully made a mapcycle.txt file.

# Adding the custom map to your newly created map cycle
Open the map cycle file you have just created.
To add a custom map, you copy this command
`workshop_MapID`.
And instead of MapID you paste the ID you have copied in the previous steps. It should look like this:
![Example Mapcycle](../images/example-mapcycle.png)
During votes, players won’t see the name but this ID number.
But if you have sourcemod installed, you can change it so players can see the name of the map.
Use the following command instead of the one above to make this happen:
`workshop/<MAPNAME>.ugc<URL-NUMBER>`