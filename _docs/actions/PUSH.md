---
layout: docs
title: PUSH
type: Actions
name: "PUSH(<array[]>,<value>)"
category: Variables
changelog:
  - type: Added
    version: v0.9.7
---
Appends `<value>` to the end of `<array[]>`

### Example
```
// Adds an element to the end of the array
PUSH(&array[],"Hello")

// The same as
&array[] = "World"

// Outputs "Hello" and "World"
FOREACH(&array[],&string)
    LOG(%&string%)
NEXT
```
