---
layout: docs
title: SLOTCLICK
type: Actions
name: "SLOTCLICK(<slot>,[button],[shift])"
category: GUI
permission: mod.macros.script.inventory.slotclick
changelog:
  - type: Updated
    version: v0.9.6
    message: "Support for creative inventory"
  - type: Added
    version: v0.9.0
---
Simulates clicking on the specified slot in the current GUI

`<slot>` can be `-999` to drop the previously selected item.

`[button]` can be either `"left"` for left-click or `"right"` for right-click

`[shift]` should be `true` if you want to shift-click
