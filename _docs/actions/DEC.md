---
layout: docs
title: DEC
type: Actions
name: "DEC(<#var>,[amount])"
category: Variables
changelog:
  - type: Added
    version: v0.8.2
---
Decrements the specified counter by 1 or by the specified amount

### Example
```
#number = 5

DEC(#number)
// Ouputs 4
LOG(%#number%)

DEC(#number,3)
// Outputs 1
LOG(%#number%)
```
