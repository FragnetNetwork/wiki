If you would like to ban or unban specific player on the server, you can follow the steps described below.

There are 2 ways of banning/unbanning players on the server which are done by editing bans.txt file and using in-chat command.

# Ban with bans.txt file

**Step 1:** Login to your account on [Fragify panel](https://panel.fragify.net/) and select your Path of Titans server.

**Step 2:** Navigate to the following directory: `PathOfTitans/Saved/` and you will need to click on **bans.txt** file to edit it.

## Formatting:
You must add each ban on a new line.

### Ban by Alderon ID
Each line in your text file must follow this format:

`AGID:UnixTimestamp:AdminReason:UserReason`

Variable|Example|Description
---|---|---
AGID|`123-443-512`|The Alderon Games ID of the player.
UnixTimestamp|`1644464516`|If the ban is temporary, enter the Unix Timestamp of the date the player will be unbanned. You can generate the timestamp here [https://www.epochconverter.com/](https://www.epochconverter.com/). If the ban is permanent, set this to `0`
AdminReason|`Admin message here!`|An internal message that will only be visible by admins. Useful for keeping notes. Can be left blank. NOTE: you cannot use a colon `:` in this description or else it will break your bans.
UserReason|`Banned for spamming the chat.`|The message the user will see when attempting to join your server. Ensure this is descriptive so the player understand why they were banned. NOTE: you cannot use a colon `:` in this description or else it will break your bans.

## Example bans.txt
```
525-053-709:0:Reason for admins here:Stay out of my server
123-456-678:1645059401:I have banned them:Broke rule number three
543-226-532:1645059400:admin note here:You are banned because you were rude
766-980-003:0::Broke rule 12 so you are permabanned.
```

**Step 3:** Ensure that the file is saved by clicking on **"Save Content"** button.

# Banning Players In-Game

## Via Chat Commands

### Ban A User
Log into your server and issue the following command: `/ban <playername> <kick reason>` Example: `/ban Jiggy Breaking rule 12`

You can leave the ban reason blank if desired.

### Unban A User
`/unban PlayerID` - Unbans the user.

### Reload Ban List
`/reloadbans` - The bans list will be refreshed ever 1 minute, however this command will reload it immiedately.