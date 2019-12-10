---
layout: docs
title: TRACE
type: Actions
name: "TRACE(<distance>,[entities])"
category: Calculations
permission: mod.macros.script.inventory.trace
changelog:
  - type: Fixed
    version: v0.14.1
    message: "X, Y, Z coordinates were not available"
  - type: Added
    version: v0.12.1
related:
  - type: Variables
    name: TRACEDATA
  - type: Variables
    name: TRACEID
  - type: Variables
    name: TRACENAME
  - type: Variables
    name: TRACESIDE
  - type: Variables
    name: TRACETYPE
  - type: Variables
    name: TRACEUUID
  - type: Variables
    name: TRACEX
  - type: Variables
    name: TRACEY
  - type: Variables
    name: TRACEZ
  - type: Variables
    name: TRACE_<name>
---
Performs a ray trace operation which sets the raytrace variables in the local scope. 

`<distance>` can be between `3` and `256`

`[entities]` can be true, if you want to include entities in your trace.

Returns the type of the result, which can be one of the following values:
* `TILE`
* `PLAYER`
* `ENTITY`
* `NONE`
