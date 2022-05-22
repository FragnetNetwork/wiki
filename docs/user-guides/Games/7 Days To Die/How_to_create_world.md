### **Create a new world, but keep the old one**

**Step 1:** Log in to your account on our [game panel](https://gamepanel.fragnet.net/) and find your service  
**Step 2:** Navigate to **Configuration Files** and press on **Text Editor** for **myserver.xml**  
**Step 3:** Find the following lines and configure them to your liking

<!-- World -->
	<property name="GameWorld"						value="Navezgane"/>			<!-- RWG (see WorldGenSeed and WorldGenSize options below) or any already existing world name in the Worlds folder (currently shipping with Navezgane) -->
	<property name="WorldGenSeed"					value=""/>				<!-- If RWG this is the seed for the generation of the new world. If a world with the resulting name already exists it will simply load it -->
	<property name="WorldGenSize"					value="4096"/>				<!-- If RWG this controls the width and height of the created world. It is also used in combination with WorldGenSeed to create the internal RWG seed thus also creating a unique map name even if using the same WorldGenSeed. Has to be between 2048 and 16384, though large map sizes will take long to generate / download / load -->
	<property name="GameName"						value="Fragnet.Net"/>			<!-- Whatever you want the game name to be. This affects the save game name as well as the seed used when placing decoration (trees etc) in the world. It does not control the generic layout of the world if creating an RWG world -->
	<property name="GameMode"						value="GameModeSurvival"/>	<!-- GameModeSurvival -->

Every line contains a detailed explanation.  
**Step 4:** Save the file and exit  
**Step 5:** Restart the server

> Keep in mind that when generating an RWG world, the value needs to be between 2048 and 16384.  
> When setting the higher value, the server will start generating a large map size, which will take long to generate / download / load the map.

### Create a new world but delete the old one

**Step 1:** Log in to your account on our [game panel](https://gamepanel.fragnet.net/) and find your service be sure to stop it before any further actions  
**Step 2:** Go to File Manager and navigate to **saves** folder  
**Step 3:** Delete all folders there. **NOTE: Do not delete any files only folders!**  
**Step 4:** Start the server

### Perform a full swipe of your server

**Step 1:** Log in to your account on our [game panel](https://gamepanel.fragnet.net/) and find your service  
**Step 2:** Press on “**… More”** button that is next to Restart  
**Step 3:** Click on **Reinstall**  
**Step 4:** Leave all default inputs and just Reinstall the service  
**Step 5:** After the reinstallation process is completed, your server should start automatically