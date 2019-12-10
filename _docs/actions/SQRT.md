---
layout: docs
title: SQRT
type: Actions
name: "SQRT(<value>,[#outvar])"
category: Calculations
changelog:
  - type: Added
    version: v0.9.10
---
Calculate the rounded square root of `<value>` and store it in `<#outvar>`.

Returns the result.

### Example
```
SQRT(100,#variant1)
#variant2 = SQRT(-50)

// Outputs 10 and 0
LOG(%#variant1%)
LOG(%#variant2%)
```
