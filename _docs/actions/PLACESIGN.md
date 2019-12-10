---
layout: docs
title: PLACESIGN
type: Actions
name: "PLACESIGN([line1],[line2],[line3],[line4],[showgui])"
category: World
permission: mod.macros.script.world.placesign
changelog:
  - type: Added
    version: v0.7.2
---
Places a sign in the world with the specified text (if you have one)

 - `[line1]` to `[line4]` specifies the content for each sign line
 - `[showgui]` should be `true` if you want to continue editing the text


### Example
```
// Places an empty sign
PLACESIGN()

// Places a sign with only one line
PLACESIGN("Hello Sign")

// Places a sign with all four lines filled in
PLACESIGN("Line 1","Line 2","Line 3","Line 4")

// Places a sign with two filled lines but leaves the GUI open
// so that you can continue to edit the sign text
PLACESIGN("Hello","World",,,true)
```
