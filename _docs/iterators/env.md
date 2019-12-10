---
layout: docs
title: env
type: Iterators
name: "env"
changelog:
  - type: Added
    version: v0.9.10
related:
  - type: Variables
    name: VARNAME
---
Iterates over all available variables

### Example
```
// Outputs the name together with the value
foreach(env)
    log("%VARNAME%: %%VARNAME%%)
next
```
