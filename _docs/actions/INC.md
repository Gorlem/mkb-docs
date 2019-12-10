---
layout: docs
title: INC
type: Actions
name: "INC(<#var>,[amount])"
category: Variables
changelog:
  - type: Added
    version: v0.8.2
---
Increments the specified counter by 1 or by the specified amount

### Example
```
#number = 1

INC(#number)
// Ouputs 2
LOG(%#number%)

INC(#number,3)
// Outputs 5
LOG(%#number%)
```
