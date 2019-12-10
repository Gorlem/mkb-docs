---
layout: docs
title: MACRONAME
type: Variables
name: "%MACRONAME%"
hidden: true
changelog:
  - type: Added
    version: v0.14.1
---
Display name of the macro.

### Example
```
FOREACH(running)
    LOG("[%MACROID%] %MACRONAME% running for %MACROTIME% seconds")
NEXT
```
