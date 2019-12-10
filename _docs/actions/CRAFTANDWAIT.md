---
layout: docs
title: CRAFTANDWAIT
type: Actions
name: "CRAFTANDWAIT(<item[:id]>,[amount],[throw],[verbose])"
category: GUI
permission: mod.macros.script.craft.craftandwait
changelog:
  - type: Updated
    version: v0.12.1
    message: "Available again"
  - type: Updated
    version: v0.11.3
    message: "New internal algorithm"
  - type: Fixed
    version: v0.9.9
    message: "Recipes with wildcard block types work now"
  - type: Fixed
    version: v0.9.4
    message: "Parses variables correctly"
  - type: Added
    version: v0.9.1
links:
  - title: Item ID Overview
    url: https://www.minecraftinfo.com/idnamelist.htm
---
Queues an auto-crafting request and waits for it to complete

### Example
```
// Crafts only once
CRAFTANDWAIT("planks")

// Crafts 12 planks
CRAFTANDWAIT("planks",12)

// Crafts 12 planks and throws it on the ground
CRAFTANDWAIT("planks",12,true)

// Logs additional messages to the chat window
CRAFTANDWAIT("planks",12,false,true)
```
