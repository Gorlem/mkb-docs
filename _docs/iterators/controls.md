---
layout: docs
title: controls
type: Iterators
name: "controls([layout][:type])"
changelog:
  - type: Added
    version: v0.13.2
related:
  - type: Variables
    name: CONTROLID
  - type: Variables
    name: CONTROLNAME
  - type: Variables
    name: CONTROLTYPE
---
Iterates over existing controls.

Can be filtered either by the layout or by the type of the control.

### Example
```
// Iterate over all controls everywhere
FOREACH(controls)

// Iterate over all controls in the layout "ingame"
FOREACH(controls(ingame))

// Iterate over all button controls
FOREACH(controls(:button))

// Iterate over all button controls in "ingame"
FOREACH(controls(ingame:button))

// Example usage, set all labels to blue
FOREACH(controls(default:label));
   SETPROPERTY(%CONTROLNAME%,"colour","blue");
NEXT;
```
