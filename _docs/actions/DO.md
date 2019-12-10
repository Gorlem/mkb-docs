---
layout: docs
title: DO
type: Actions
name: "DO([count])"
category: Control Flow
changelog:
  - type: Fixed
    version: v0.8.5
    message: "Parses variables correctly"
  - type: Added
    version: v0.6.0
related:
  - type: Actions
    name: LOOP
  - type: Actions
    name: UNTIL
  - type: Actions
    name: WHILE
---
Begins a loop.

When used together with `LOOP` you can specify an amount of loops. When not specified it will loop forever.

Can also be used together with `WHILE` or `UNTIL`.
