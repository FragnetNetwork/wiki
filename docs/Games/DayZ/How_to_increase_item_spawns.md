Making changes to the drop loot table can be tricky, but once you are able to understand its functions and purpose, you will be able to ninja add new items in notime. This guide will help you going trough the process of applying changes to the dayz loot table.


## Where to Start?


firstly, you have to know what you would like to change. In this guide, we are going to increase the amount of spawns for the item "shovel". To edit the amount of a select item that spawns on the map, you will have to open up the "types.xml" file.

  

- Navigate to your gamepanel.

- Now from the dashboard, on the left-hand side, go to `File Manager > mpmissions >dayzOffline.chernarusplus > db`

- Now click on and open your **"types.xml"**

----------

### Item Values

  

- Once inside the file, you will notice a lot of coding and itemnames. These are all the items that you can find ingame. They are preset and defined depending on their locations.

- Making changes to these values will have different effects. Here is a basis of what each line of an item does:

  

| Value | Description |
|--|--|
| Nominal | How many of this item that can be on the map. |
|lifetime|The lifetime of an item once it is spawned. (Time in seconds)|
| restock| The amount of time that will need to pass before an item is allowed to spawn again. |
|min|The minimum amount of an item that will spawn on the map.|
| quantmin| Dictates the minimum quantity of consumable within the item. Value=(-1.0%(empty) - 100.0%(full)) This is how many bullets are in an Ammo box, or how much water is in a bottle) |
|quantmax|Dictates the maximum quantity of consumable within the item. Value=(-1.0%(empty) - 100.0%(full) This is how many bullets are in an Ammo box, or how much water is in a bottle)|
| Cost | Determines the spawn chance of an item. |
|Catergory|The category of an item. Effects on how and where the item spawns. (Weapons, Tools, Containers, Clothes, ect.)|
| Useage | The group in which area an item will spawn. (Farm, Industrial, Medic, Hunting, ect.) |
|Value|The value group of an item. Effects on how and where the item spawns. (Tier1, Tier2, Tier3, ect.)|

  

1. As we want to change the spawn amount of the item "shovel" you have to find the section first for this. ( tip: use the search bar option in the editor to quikly find your item that you want to edit. )

2. When you have found the shovel item, it would be looking something like this.

![Example Item](../images/item-shovel.png)

3. As we have explained above in the first section on what each line of
text means, it would mean that we have to edit the "min" option.

4. Once changed to your desired needs, hit the save button. 

Go back to our game panel and restart your server. 
Success! You just changed the amount of spawns on your server for the shovel! You should be good to go.

If there would be any questions, we are happy to help you out on our official discord channel!