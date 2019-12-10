---
layout: docs
title: ARRAYSIZE
type: Actions
name: "ARRAYSIZE(<array[]>,[#outvar])"
category: Variables
changelog:
  - type: Added
    version: v0.9.7
---
Stores the size of the specified `<array[]>` in `[#outvar]`.

Returns the size of the array.

### Example
```
&array[] = "Hello"
&array[] = "World"

ARRAYSIZE(&array[],#variant1)

&array[] = "Bigger"

#variant2 = ARRAYSIZE(&array[])

// Output 2 and 3 respectively
LOG(%#variant1%)
LOG(%#variant2%)
```
