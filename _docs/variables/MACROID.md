---
layout: docs
title: MACROID
type: Variables
name: "%MACROID%"
hidden: true
changelog:
  - type: Added
    version: v0.14.1
---
Internal id of the macro.

### Example
```
FOREACH(running)
    LOG("[%MACROID%] %MACRONAME% running for %MACROTIME% seconds")
NEXT
```
