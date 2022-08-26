In this guide, we are going to use console commands.
# How to ban a player
1. Firstly navigate to your console on your Fragify game panel.
When a player connects, the console will type out the player's name and IP.
It should look something like this:
```
Client "Test" connected (12.34.567.890:11111).
``` 
To ban a player via IP, you need to type in:
```
addip <Minutes> <IP>
```
An example like this:
```
addip 0 12.34.567.890
```
And it will ban the player right away (0 meaning that it's permanent, or you can choose how many minutes you want the player to be banned).
After that, type in the command
```
writeip
```
As this will save the bans in the **banned_ip.cfg** and the player will be permanently banned

# How to unban a player
Unbanning players is straightforward, you navigate to your console and type in
```
removeip IP 
```
example: 
```
removeip 12.34.567.890
```
And after, type in:
```
writeip
```