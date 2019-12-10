---
layout: docs
title: PUT
type: Actions
name: "PUT(<array[]>,<value>)"
category: Variables
changelog:
  - type: Added
    version: v0.9.7
---
Inserts `<value>` at the first empty point in `<array[]>`.

### Example
```
&array[0] = "Hello"
&array[2] = "World"

// Adds an element at the first empty point in the array
PUT(&array[],"Inserted")

// Outputs "Hello", "Inserted" and "World"
FOREACH(&array[],&string)
    LOG(%&string%)
NEXT
```
