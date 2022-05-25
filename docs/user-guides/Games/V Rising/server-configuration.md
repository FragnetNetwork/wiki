# Server Configuration

## There are two main settings files that the server is using.
- `ServerHostSettings.json`
- `ServerGameSettings.json`

In order to edit those files, head over to your game panel -> **Configuration Files**

### ServerHostSettings.json
Here you can edit the following settings:

!!! info
    After making changes to this file, make sure to restart your server so the changes take effect.

| Setting | Value Type | Example Value | Comment |
|----------|:-------------:|:------:|---|
| Name | string | "My V Rising Server" | Name of server |
| Description | string | "This is a role playing server" | Short description of server purpose, rules, message of the day |
| MaxConnectedAdmins | number | 4 | Max number of admins to allow connect even when server is full |
| SaveName | string | "world1" | Name of save file/directory |
| Password | string | "SuperSecret" | Set a password or leave empty |
| ListOnMasterServer | boolean | true | Set to true to list on server list, else set to false |
| AutoSaveCount | number | 40 | Number of autosaves to keep |
| AutoSaveInterval | number | 120 | Interval in seconds between each auto save |
| GameSettingsPreset | string | "StandardPvP" | Name of a GameSettings preset found in the GameSettingPresets folder |


### ServerGameSettings.json
| Setting | Example Values | Comment |
|----------|:------------:|---------|
| GameModeType | PvP<br>PvE | Sets the kind of game mode you're playing. |
| CastleDamageMode | Always<br>Never<br>TimeRestricted | Sets when Castles can be damaged. "TimeRestricted" uses VSCastle times. |
| SiegeWeaponHealth |  | Determines the health of Siege Weapons. |
| PlayerDamageMode | Always<br>TimeRestricted | Determines whether or not other players can be damaged. "TimeRestricted" uses VsPlayer times. |
| CastleHeartDamageMode | CanBeDestroyedOnlyWhenDecaying<br>CanBeDestroyedByPlayers<br>CanBeSeizedOrDestroyedByPlayers | Determines how and when Castle Hearts can be destroyed or seized. |
| PvPProtectionMode | Short<br>Medium<br>Long | This is the protection you get when you first make your character that prevents newbies from being slaughtered in PvP | 
| DeathContainerPermission | Anyone<br>ClanMembers | Basically who can and can not access your bags when you die. |
| RelicSpawnType | Unique<br>Plentiful | Makes each of the Soul Shards unique or allows there to be more than one of each of the Soul Shards (plentiful). |
| CanLootEnemyContainers | True<br>False | This determines whether or not a random person sneaking into your base can access your chests and other containers. |
| BloodBoundEquipment | True<br>False | Lose or keep your equipment upon death. |
| TeleportBoundItems | True<br>False | When using a Vampire Waygate you can turn this on or off to determine if your items travel with you. |
| AllowGlobalChat | True<br>False | Turns Global Chat on or off. |
| AllWaypointsUnlocked | True<br>False | Reveals or conceals Vampire Waygates. |
| FreeCastleClaim | True<br>False | This allows people to claim a castle without paying a resource cost. |
| FreeCastleDestroy | True<br>False | Same as above but in regards to being destroyed whether or not there is a cost. |
| InactivityKillEnabled | True<br>False | AFK timer which kills you if you are detected inactive. |
| InactivityKillTimeMin | 3600 | Related to the above function. |
| InactivityKillTimeMax | 604800 | |
| InactivityKillSafeTimeAddition | 172800 | Unknown. |
| InactivityKillTimerMaxItemLevel | 84 | Unknown. |
| DisableDisconnectedDeadEnabled | True<br>False | Unknown. |
| DisableDisconnectedDeadTimer | 60 | Unknown. |
| InventoryStacksModifier | 1.0 | The size of your inventory stacks. |
| DropTableModifier_General | 1.0 | Increase or decrease the amount of loot that drops from enemies. |
| DropTableModifier_Missions | 1.0 | Same as above but for missions. |
| MaterialYieldModifier_Global | 1.0 | This modifies the amount you get from a resource node like a stone or copper. |
| BloodEssenceYieldModifier | 1.0 | This changes how much Blood Essence you gain from killing enemies. |
| JournalVBloodSourceUnitMaxDistance | 25.0 | Max tracking distance. |
| PvPVampireRespawnModifier | 1.0 | This is how long it takes you to respawn after being killed in PvP. |
| CastleMinimumDistanceInFloors | 2 | This is how far away someone else’s boundaries must be. Increase this to prevent base trapping. |
| ClanSize | 4 | Determines the maximum size of a Clan. |
| BloodDrainModifier | 1.0 | How much your blood level drains. |
| DurabilityDrainModifier | 1.0 | This determines how much the durability drains. |
| GarlicAreaStrengthModifier | 1.0 | Modifies the strength of Garlic areas. |
| HolyAreaStrengthModifier | 1.0 | Modifies the strength of Holy areas. |
| SilverStrengthModifier | 1.0 | Modifies the strength of the Silver debuff. |
| SunDamageModifier | 1.0 | Modifies the strength of the Sun debuff. |
| CastleDecayRateModifier | 1.0 | Modifies the rate at which Castles decay. |
| CastleBloodEssenceDrainModifier | 1.0 | Modifies the rate at which Castles drain stored Blood Essence. | 
| CastleSiegeTimer | 420.0 | How long a Castle can be sieged by another player. |
| CastleUnderAttackTimer | 60.0 | How long a castle can be under attack. |
| AnnounceSiegeWeaponSpawn | True<br>False | Announces the deployment of a Siege Weapon on the server. |
| ShowSiegeWeaponMapIcon | True<br>False | This will display the Siege Weapon on the map. |
| BuildCostModifier | 1.0 | Modifies the cost for buildings. |
| RecipeCostModifier | 1.0 | Modifies the cost for crafting. |
| CraftRateModifier |  1.0 | Modifies the speed of crafting. |
| ResearchCostModifier | 1.0 | Modifies the cost of research. |
| RefinementCostModifier | 1.0 | Modifies the cost of Refining. |
| RefinementRateModifier | 1.0 | Modifies the speed of Refining. |
| ResearchTimeModifier | 1.0 | Modifies the speed of Research. | 
| DismantleResourceModifier | 0.75 | This is how much you get back after dismantling something like a wall. |
| ServantConvertRateModifier | 1.0 | Time it takes to convert a Servant. |
| RepairCostModifier | Default 1.0 | Increases or decreases the repair costs for buildings. |
| Death_DurabilityFactorLoss | 0.25 | Durability loss when killed. |
| Death_DurabilityLossFactorAsResources | 1.0 | How much gear you lose when dying. 0.5 = 50% |
| StarterEquipmentId | 0<br>Gear Level 30: -376135143<br>Gear Level 50: -1613823352<br>Gear Level 70: -255898606 | This is what equipment you start with. |
| StarterResourcesId | 0<br>Gear Level 30: -696202180<br>Gear Level 50: 481718792<br>Gear Level 70: -766909665 | Instead of straight giving the players gear it gives them a lot of resources instead. |
| CastleLimit | 2 | Sets limits on your Castle as well as it’s stats. |
| Timezone | Local<br>UTC<br>PST<br>EST<br>CET<br>CST | Time zone for your server. |
| VSPlayerWeekdayTime | | PvP start and stop times. Keep in mind it must ONLY be the current day. DO NOT attempt to set the start time for example at 23:00 and end time at 08:00 the next day. All times must be in the day. I have found the server to behave strangely when this is done. |
| VSPlayerWeekendTime | | Weekend PvP times. |
| VSCastleWeekdayTime | | Castle siege times during weekdays. |
| VSCastleWeekendTime | | Castle siege times during the weekend. |