---
layout: docs
title: REASON
type: Variables
name: "%REASON%"
hidden: true
changelog:
  - type: Updated
    version: v0.9.9
    message: "Returns `NORECIPE` when no recipe is found. Previously returned `NOTSTARTED`"
  - type: Added
    version: v0.9.0
---
The reason why the crafting was completed or aborted.

Can be one of the following values:

* `DONE`
* `CREATIVE`
* `NORECIPE`
* `NOTSTARTED`
* `TIMEOUT`
* `NOITEMS`
* `ERROR`
* `NOSPACE`
