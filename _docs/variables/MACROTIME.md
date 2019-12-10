---
layout: docs
title: MACROTIME
type: Variables
name: "%MACROTIME%"
hidden: true
changelog:
  - type: Added
    version: v0.14.1
---
The time the macro is already running in seconds.

### Example
```
FOREACH(running)
    LOG("[%MACROID%] %MACRONAME% running for %MACROTIME% seconds")
NEXT
```
