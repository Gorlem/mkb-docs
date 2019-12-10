---
layout: docs
title: PICK
type: Actions
name: "PICK(<item[:damage]>,[item[:damage]],...)"
category: GUI
permission: mod.macros.script.inventory.pick
changelog:
  - type: Fixed
    version: v0.15.1
    message: "Work correctly with enchanted items"
  - type: Fixed
    version: v0.9.4
    message: "Parses variables correctly"
  - type: Updated
    version: v0.9.0
    message: "Now supports multiple item id's and also damage values"
  - type: Added
    version: v0.6.0
links:
  - title: Item ID Overview
    url: https://www.minecraftinfo.com/idnamelist.htm
---
Selects the specified item id if it is on the hotbar, specify multiple items to pick in order of preference.

Returns the selected item name.
