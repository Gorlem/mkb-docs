---
layout: docs
title: DECODE
type: Actions
name: "DECODE(<input>,[&output])"
category: Calculations
changelog:
  - type: Added
    version: v0.9.10
links:
  - title: Base 64
    url: https://en.wikipedia.org/wiki/Base64
---
Converts an string from base64 back to an normal string.

Returns the decoded string.

### Example
```
&string = "SGVsbG8gV29ybGQ="

DECODE(%&string%,&variant1)
&variant2 = DECODE(%&string%)

// Both output "Hello World"
LOG(%&variant1%)
LOG(%&variant2%)
```
