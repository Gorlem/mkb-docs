---
layout: docs
title: GETID
type: Actions
name: "GETID(<x>,<y>,<z>,[&idvar],[#datavar])"
category: Calculations
permission: mod.macros.script.inventory.getid
changelog:
  - type: Updated
    version: v0.10.4
    message: "Minecraft-style relative locations by prepending `~` to the coordinates"
  - type: Updated
    version: v0.9.5
    message: "Added and then removed relative syntax (`+` and `-`), because it broke negative coordinates"
  - type: Updated
    version: v0.9.5
    message: "New fifth parameter to retrieve the block metadata"
  - type: Added
    version: v0.8.6
links:
  - title: Item ID Overview
    url: https://www.minecraftinfo.com/idnamelist.htm
---
Gets the ID and optionally the data value of the block at the specified coordinates in the world.

Returns the name of the block.

### Example
```
GETID(0,32,0,&variant1)
&variant2 = GETID(0,32,0,,#data)
```
