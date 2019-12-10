---
layout: docs
title: FOV
type: Actions
name: "FOV(<value>,[time])"
category: Settings
permission: mod.macros.script.option.fov
changelog:
  - type: Fixed
    version: v0.9.8
    message: "Parses variables correctly"
  - type: Added
    version: v0.5.0
---
Sets the FOV angle in degrees, specifying time causes the value to change smoothly.

`<value>` has to be between `70` and `110`.
