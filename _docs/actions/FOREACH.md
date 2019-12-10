---
layout: docs
title: FOREACH
type: Actions
name: "FOREACH(<iterator>)"
category: Control Flow
changelog:
  - type: Updated
    version: v0.9.7
    message: "Supports iterating over arrays"
  - type: Added
    version: v0.9.0
related:
  - type: Actions
    name: BREAK
  - type: Actions
    name: NEXT
---
Runs a loop over the specified iterator.
Needs to be closed with `NEXT`.

The iterator can either be [one of the these](/docs/iterators/) or an array.

The loop can be stopped early by using `BREAK`.

Alternative Syntax:
```
FOREACH(<&array[]>,<&content>,[#index])
FOREACH(<&array[]> as <&content>)
FOREACH(<&array[]> as <#index> => <&content>)
```
