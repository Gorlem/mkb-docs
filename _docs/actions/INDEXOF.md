---
layout: docs
title: INDEXOF
type: Actions
name: "INDEXOF(<array[]>,<#outvar>,<searchfor>,[casesensitiv])"
category: Variables
changelog:
  - type: Updated
    version: v0.9.10
    message: "New fourth parameter which will force a case-sensitive lookup"
  - type: Added
    version: v0.9.7
---
Gets the first index of `<searchfor>` in `<array[]>` and stores it in `<#outvar>`.

`[casesensitiv]` can be set to `true` which will cause the check to be case-sensitiv. (By default the search is case-insensitiv.)

Returns the found index.

### Example
```
&array[] = "Looking"
&array[] = "for"
&array[] = "Hello"
&array[] = "World"

INDEXOF(&array[],#variant1,"Hello")
#variant2 = INDEXOF(&array[],,"Not here")

// Output 2 and -1 respectively
LOG(%#variant1%)
LOG(%#variant2%)
```
