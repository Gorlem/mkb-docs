---
layout: docs
title: ENCODE
type: Actions
name: "ENCODE(<input>,[&output])"
category: Calculations
changelog:
  - type: Added
    version: v0.9.10
links:
  - title: Base 64
    url: https://en.wikipedia.org/wiki/Base64
---
Converts an string to base 64.

Returns the encoded value.

### Example
```
&string = "Hello World"

ENCODE(%&string%,&variant1)
&variant2 = ENCODE(%&string%)

// Both output "SGVsbG8gV29ybGQ="
LOG(%&variant1%)
LOG(%&variant2%)
```
