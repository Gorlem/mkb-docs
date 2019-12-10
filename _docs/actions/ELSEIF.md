---
layout: docs
title: ELSEIF
type: Actions
name: "ELSEIF(<condition>)"
category: Control Flow
changelog:
  - type: Added
    version: v0.8.2
---
The actions following this action will only be executed when the `<condition>` evaluates to `true` and no if-clause before evaluated to true.

Can be used with:

* `IF`
* `IFBEGINSWITH`
* `IFCONTAINS`
* `IFENDSWITH`
* `IFMATCHES`

