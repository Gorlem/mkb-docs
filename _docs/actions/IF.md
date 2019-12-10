---
layout: docs
title: IF
type: Actions
name: "IF(<condition>)"
category: Control Flow
changelog:
  - type: Added
    version: v0.7.2
related:
  - type: Actions
    name: ELSE
  - type: Actions
    name: ELSEIF
  - type: Actions
    name: ENDIF
---
The actions following this action will only be executed when the `<condition>` evaluates to `true`.

Needs to be closed with an `ENDIF`.
