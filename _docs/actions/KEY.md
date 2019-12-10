---
layout: docs
title: KEY
type: Actions
name: "KEY(<bind>)"
category: Input
permission: mod.macros.script.input.key
changelog:
  - type: Updated
    version: v0.10.4
    message: "New possible values `\"screenshot\"` and `\"smoothcamera\"`"
  - type: Fixed
    version: v0.9.6
    message: "Parses variables correctly"
  - type: Fixed
    version: v0.7.2
    message: "`\"attack\"` and `\"use\"` were not working as expected"
  - type: Added
    version: v0.5.0
---
Activates the specified key binding for 1 tick

Can be one of the following values:
 * `"inventory"`
 * `"drop"`
 * `"chat"`
 * `"attack"`
 * `"use"`
 * `"pick"`
 * `"screenshot"`
 * `"smoothcamera"`
 * `"swaphands"`

