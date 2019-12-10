---
layout: docs
title: STOP
type: Actions
name: "STOP([id])"
category: Control Flow
changelog:
  - type: Updated
    version: v0.10.12
    message: "Variables can be used as arguments"
  - type: Updated
    version: v0.8.5
    message: "New possible values `\"all\"` or `\"*\"` to stop all active macros"
  - type: Added
    version: v0.6.0
---
Stops the current macro, or macros matching the specified ID

For stopping all macros you can use either `"all"` or `"*"`.
