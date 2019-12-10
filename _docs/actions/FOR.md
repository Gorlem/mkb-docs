---
layout: docs
title: FOR
type: Actions
name: "FOR(<#var>,<start>,<end>,[step])"
category: Control Flow
changelog:
  - type: Updated
    version: v0.12.1
    message: "Can now set step value"
  - type: Added
    version: v0.9.0
related:
  - type: Actions
    name: BREAK
  - type: Actions
    name: NEXT
---
Begins a for loop using the specified var as a loop counter.
Needs to be closed with `NEXT`.

The loop can be stopped early by using `BREAK`.

Alternative syntax:
```
FOR(<#var> = <start> to <end>)
FOR(<#var> = <start> to <end> step <step>)
```

__Bug!__
The `[step]` parameter in the default syntax currently does not work.
