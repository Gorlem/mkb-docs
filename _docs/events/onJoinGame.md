---
layout: docs
title: onJoinGame
type: Events
name: "onJoinGame"
changelog:
  - type: Fixed
    version: v0.13.0
    message: "Was occasionally not working"
  - type: Fixed
    version: v0.9.10
    message: "After a kick or an disconnect the event get triggered properly now"
  - type: Added
    version: v0.8.5
---
Raised whenever you join a game (single player or SMP)

Can be used to start background macros or issue server commands when joining a new game
