---
layout: docs
title: JOIN
type: Actions
name: "JOIN(<glue>,<array[]>,[&output])"
category: Variables
changelog:
  - type: Added
    version: v0.9.10
---
Combines all values inside `<array[]>` with `<glue>` and stores it optionally in `[&output]`.

Returns the output.

### Example
```
&array[] = "Join"
&array[] = "Hello"
&array[] = "World"

JOIN("--",&array[],&variant1)
&variant2 = JOIN(", ",&array[])

// Outputs "Join--Hello--World"
LOG(%&variant1%)

// Outputs "Join, Hello, World"
LOG(%&variant2%)
```
