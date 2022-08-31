1\. If you are currently using vanilla or tModLoader Terraria versions, you can find out how to switch to TShock [here](How_to_switch_between_vanilla_Terraria,_tModLoader_and_TShock.md).

2\. Start your TShock Terraria server and go to **File Manager** option on the left-side menu. Go to `tshock` folder and you will find here `setup-code.txt` file. Open it by clicking on it and you can see numeric code that we are going to use for becoming admin on the server. 

![File Manager](../images/file-manager.png)

![Setup Code](../images/setup-code.png)

3\. Open the game and join your server. You will need to press `Enter` key to type in chat window:
```
/setup yourSetupCode
```
Example:

![Example Setup Code](../images/example-setup-code.png)

After entering the code, you will see the following message:

![Message for Admin](../images/message-admin.png)

4\. You will need to input the following command:
```
 /user add yourUsername yourPassword owner
```
Afterwards, input:
```
/login yourUsername yourPassword
```

You have added and became succesfully admin to your TShock server!