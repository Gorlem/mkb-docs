---
layout: docs
title: UCASE
type: Actions
name: "UCASE(<input>,[&output])"
category: Calculations
changelog:
  - type: Added
    version: v0.10.4
---
Converts the input string to upper case and stores it in output.

Returns the output.

### Example
```
&string = "HeLLo wORLd"

UCASE(%&string%,&variant1)
&variant2 = UCASE(%&string%)

// Both output "HELLO WORLD"
LOG(%&variant1%)
LOG(%&variant2%)
```
