---
layout: docs
title: KEYUP
type: Actions
name: "KEYUP(<bind>)"
category: Input
permission: mod.macros.script.input.keyup
changelog:
  - type: Updated
    version: v0.10.4
    message: "New possible values `\"playerlist\"` and `\"sprint\"`"
  - type: Fixed
    version: v0.9.6
    message: "Parses variables correctly"
  - type: Added
    version: v0.5.0
---
Sets the specified key binding state to unpressed, only works with pressable bindings

Can be one of the following values:

 * `"forward"`
 * `"back"`
 * `"left"`
 * `"right"`
 * `"jump"`
 * `"sneak"`
 * `"playerlist"`
 * `"sprint"`

Can also be a key code value between 0 and 255
