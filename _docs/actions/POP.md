---
layout: docs
title: POP
type: Actions
name: "POP(<array[]>,<outvar>)"
category: Variables
changelog:
  - type: Added
    version: v0.9.7
---
Removes the last entry from the end of `<array[]>` and stores it in `<outvar>`.

Returns the popped element.

### Example
```
&array[] = "Hello"
&array[] = "World"

POP(&array[],&string)

// Outputs "World"
LOG(%&string%)
```
