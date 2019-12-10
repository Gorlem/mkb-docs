---
layout: docs
title: RANDOM
type: Actions
name: "RANDOM(<#target>,[max],[min])"
category: Calculations
changelog:
  - type: Added
    version: v0.8.7
---
Assigns a random number between min and max to target.

Returns the value.

### Example
```
#variant1 = RANDOM()
RANDOM(#variant2)
// By default generate a random integer between 0 and 100

RANDOM(,1)
// Either 0 or 1

RANDOM(,5,10)
// Between 5 and 10

RANDOM(,10,5)
// Also between 5 and 10 (Ordering is not important)
```
