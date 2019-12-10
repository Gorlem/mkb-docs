---
layout: docs
title: STRIP
type: Actions
name: "STRIP(<&target>,<text>)"
category: Calculations
changelog:
  - type: Added
    version: v0.9.0
links:
  - title: Formatting Codes
    url: http://minecraft.gamepedia.com/Formatting_codes
---
Strips all formatting codes from the specified `<text>` and assigns the result to `<&target>`.

Returns the result.

### Example
```
&string = "§eyellow §r§lbold"

STRIP(&variant1,%&string%)
&variant2 = STRIP(,%&string%)

// Both output "yellow bold"
LOG(%&variant1%)
LOG(%&variant2%)
```
