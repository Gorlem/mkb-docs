---
layout: docs
title: GETIDREL
type: Actions
name: "GETIDREL(<xoffset>,<yoffset>,<zoffset>,[&idvar],[#datavar])"
category: Calculations
permission: mod.macros.script.inventory.getidrel
changelog:
  - type: Added
    version: v0.9.5
links:
  - title: Item ID Overview
    url: https://www.minecraftinfo.com/idnamelist.htm
---
Gets the ID and optionally the data value of the block at the specified coordinates relative to the player.

Returns the name of the block.

### Example
```
// Retrieves information about the block below the player
GETIDREL(0,-1,0,&variant1)
&variant2 = GETIDREL(0,-1,0,,#data)
```
