---
layout: docs
title: FOG
type: Actions
name: "FOG([value])"
category: Settings
permission: mod.macros.script.option.fog
changelog:
  - type: Updated
    version: v0.10.4
    message: "Now also accepts the chunks distance as a number"
  - type: Updated
    version: v0.8.6
    message: "New possible values `\"far\"`, `\"normal\"`, `\"short\"` and `\"tiny\"`"
  - type: Added
    version: v0.5.0
---
Toggles render distance, or optionally specify render distance

Can be one of the following values:

 * `"far"` for 16 chunks
 * `"normal"` for 8 chunks
 * `"short"` for 4 chunks
 * `"tiny"` for 2 chunks

Alternatively the amount of chunks (up to 16) can also be specified directly
