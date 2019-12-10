---
layout: docs
title: REPLACE
type: Actions
name: "REPLACE(<&subject>,<search>,[replace])"
category: Calculations
changelog:
  - type: Added
    version: v0.9.4
---
Replace all occurrences of `<search>` with `[replace]` in `<&subject>`.

Returns the new string.

### Example
```
&string = "Looking for Hello World"

// Deletes "for" from &string
REPLACE(&string,"for")
// Ouputs "Looking  Hello World"
LOG(%&string%)

// Replaces "Hello" with the given string
REPLACE(&string,"Hello","Bye")
// Outputs "Looking  Bye World"
LOG(%&string%)

// Doesn't modify &string
&result = REPLACE(&string,"World","Level")
// Outputs "Looking  Bye Level" and "Looking  Bye World" respectively
LOG(%&result%)
LOG(%&string%)
```
