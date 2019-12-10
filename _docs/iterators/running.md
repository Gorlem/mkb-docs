---
layout: docs
title: running
type: Iterators
name: "running"
changelog:
  - type: Added
    version: v0.14.1
related:
  - type: Variables
    name: MACROID
  - type: Variables
    name: MACRONAME
  - type: Variables
    name: MACROTIME
---
Iterates over all currently running macros

### Example
```
FOREACH(running)
    LOG("[%MACROID%] %MACRONAME% running for %MACROTIME% seconds")
NEXT
```
