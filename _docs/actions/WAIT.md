---
layout: docs
title: WAIT
type: Actions
name: "WAIT(<time>)"
category: Control Flow
changelog:
  - type: Updated
    version: v0.9.4
    message: "wait time can be now be specified in ticks by appending `t` to the value"
  - type: Added
    version: v0.5.0
---
Pauses the script for the time (in seconds) specified, suffix `ms` for a wait in milliseconds or `t` to wait in ticks.
