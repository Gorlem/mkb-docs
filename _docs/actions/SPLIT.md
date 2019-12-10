---
layout: docs
title: SPLIT
type: Actions
name: "SPLIT(<delimiter>,<source>,[output[]])"
category: Variables
changelog:
  - type: Added
    version: v0.9.10
---
Splits the supplied `<source>` string on every `<delimiter>` into `<output[]>`.

Returns the output array.

### Example
```
&string = "Split Hello World"

SPLIT(" ",%&string%,&variant1[])
&variant2[] = SPLIT("o",%&string%)

// Outputs "Split", "Hello" and "World"
FOREACH(&variant1[],&string)
    LOG(%&string%)
NEXT

// Outputs "Split Hell", " W" and "rld"
FOREACH(&variant2[],&string)
    LOG(%&string%)
NEXT
```
