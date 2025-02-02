# Ravenspear Contract Wars

Ravenspear Contract Wars (RCW) is a DCS mission being created for the Ravenspear Tactical Solutions DCS community.

This repository is mainly used for organisation and staging purposes when it comes to the scripts involved.

Currently the mission is in a non-functioning state as it is missing a number of key features.

If you have any questions regarding this repository, please join the Ravenspear Discord where you are welcome to ask questions: https://discord.gg/2DvxuKfMdM

# Current Mission Features

###### Persistence

The RCW Persistence Module saves the state of all ground units, ships and static objects in the mission. This allows a DCS server/session to be stopped and started and continued from where it was. The current version of this module supports the saving of ground units and ships. Ships to be skipped can be added into the shipWhitelist at the top of the file. This should be used if there are ships with slots on them (eg. carrier Tomcat slots) or serious issues will occur as ships with slots cannot be respawned while maintaining slot functionality.

###### Armament Tracker (WIP/Not In Use)

The RCW Armament Module allows for player armament and weapons loadouts to become persistent, operating from a weapons stockpile that can be either manually controlled or automatically updated by external sources. When players take off from airfields, the weapons on their aircraft are subtracted from stockpiles, and when they land, any remaining weapons are returned to the same stockpiles. If players take off with an invalid loadout, they are warned and given time to land, and if they continue to fly with the invalid loadout they are destroyed.

###### Air Patrol Spawner (WIP)

Enemy patrols spawn from a pre-defined pool based on friendly trespass into static incursion zones. This can be customised to allow for different pools of aircraft to be scrambled depending on the airbase, as well as what distance to scramble a patrol, as well as which airbases will be allowed to field patrols.

###### Game Master Script (Heavy WIP)

Human game masters are able to spawn air and ground units into the mission based on predefined presets.

# To Do

Additional features are being developed before a v1.00 of the mission is "released". This includes more depth to the air spawning system, more ground templates for human game masters to use as well as documentation, and finally air patrol spawn definitions for the Air Patrol Spawner.

# Credits

RCW uses several functions from the MOOSE scripting framework: https://github.com/FlightControl-Master/MOOSE

Credit to Pikey for his Simple Group Saving and Simple Static Saving scripts, which were modified for this project: https://github.com/thebgpikester/SimpleGroupSaving

https://github.com/thebgpikester/SimpleStaticSaving

Credit to CakeSorbus for his Enhanced Gamemaster Script: https://forum.dcs.world/topic/244688-enhanced-gamemaster-script-zeus-but-for-dcs/


