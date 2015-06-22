## Enhanced Portals: Changelog

### 3.0.12
Added:
* Diamond nugget for use with TE recipes.

Fixed:
* Thermal Expansion recipes.
* Missing recipe for Fluid Module Upgrade.
* Ender-Infused metal recipe.

Removed:
* Reverted transparent frame blocks.

### 3.0.11
Added:
* Thermal Expansion recipes.
* [#184] Ability to disable Thermal Expansion and Vanilla crafting recipes independently.
* Ability to use transparent blocks for portal frames.

Changed:
* Featherfall now works as a Potion Effect that lasts for 10 seconds after you hit the portal that contains the module.

Fixed:
* [#174] Update check every time a player joins a server for both the client and server.
* [#183] Module Manipulator incorrectly syncing data to client.
* Tiny buttons on Dimensional Bridge Stabilizer GUI.
* Graphical issues on guide book.
* Memory leak on guide book item information pages.
* Direct redstone issues. Redstone torches can now be placed directly onto the Redstone Interface and redstone wire now works directly.
* Chat messages will now always correctly display [Success] or [Error].

### 3.0.10
* Cleaned out code referring to Buildcraft's old Mj API, should now work fine with 6.3+

### 3.0.9
* #165
* #156
* #139
* Entity rotation with a module manipulator installed, but no rotation module.
* Odd looking slider on the colour tabs.
* Can now change UID from saved destinations in the dialing device.

### 3.0.8
* Lang file in CZ - Thanks Nalimleinad
* Lang file in CH - Thanks Mazdallier
* Lang file in FR - Thanks Mrkwtkr
* OpenComputers updated to 1.4 - Thanks fnuecke

### 3.0.7
* Lang file in RU - Thanks Merkaba5
* Temporary fix for #142, lengthening the # of blocks checked by the controller to see the other side of a portal frame before giving up on verifying if a portal can be established.
* NEI fix for the nasty #140 bug - Thanks RoyCurtis

### 3.0.6
* Reinstated the instability effects. The chance of the effect happening is proportional to the % of instability.