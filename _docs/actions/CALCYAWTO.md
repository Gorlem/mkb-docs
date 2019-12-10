---
layout: docs
title: CALCYAWTO
type: Actions
name: "CALCYAWTO(<xpos>,<zpos>,[#yaw],[#distance])"
category: Calculations
changelog:
  - type: Added
    version: v0.9.10
---
Calculates the absolute yaw angle and optionally the distance to the specified coordinates.

Returns the calculated yaw value.

### Example
```
CALCYAWTO(0,0,#variant1,#distance)
#variant2 = CALCYAWTO(0,0,,#distance)

// If you want to use this yaw value you have to add 180, because of legacy reasons
INC(#variant1,180)
LOOK(%#variant1%)

LOG(%#distance%)
```
