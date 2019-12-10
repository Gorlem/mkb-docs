---
layout: docs
title: PLAYSOUND
type: Actions
name: "PLAYSOUND(<sound>,[volume])"
category: World
changelog:
  - type: Fixed
    version: v0.14.4
    message: "Custom sounds not working"
  - type: Fixed
    version: v0.13.2
    message: "Can now play sounds with underscores"
  - type: Updated
    version: v0.9.8
    message: "Now accepts a second argument to specify the volume"
  - type: Added
    version: v0.8.7
---
Plays the specified sound.

If the `<sound>` starts with `"custom."` it looks inside an folder `sounds` inside the macros config folder.

`[volume]` has to be betweem `0` and `100`



### Example
```
PLAYSOUND("entity.creeper.primed")

// Has to be in .ogg format
PLAYSOUND("custom.sound")
```
