---
layout: docs
title: VARNAME
type: Variables
name: "%VARNAME%"
hidden: true
changelog:
  - type: Added
    version: v0.9.10
---
Contains the variable name.

### Example
```
// Outputs the name together with the value
foreach(env)
    log("%VARNAME%: %%VARNAME%%)
next
```
