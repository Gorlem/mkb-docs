---
layout: docs
title: LCASE
type: Actions
name: "LCASE(<input>,[&output])"
category: Calculations
changelog:
  - type: Added
    version: v0.10.4
---
Converts the input string to lower case and stores it in output.

Returns the output.

### Example
```
&string = "HeLLo wORLd"

LCASE(%&string%,&variant1)
&variant2 = LCASE(%&string%)

// Both output "hello world"
LOG(%&variant1%)
LOG(%&variant2%)
```
