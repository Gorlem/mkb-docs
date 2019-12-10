---
layout: docs
title: IFMATCHES
type: Actions
name: "IFMATCHES(<subject>,<pattern>,[&target],[group])"
category: Control Flow
changelog:
  - type: Updated
    version: v0.9.0
    message: "Can now store the match"
  - type: Added
    version: v0.8.5
links:
  - title: Regular Expressions QuickStart
    url: http://www.regular-expressions.info/quickstart.html
  - title: Regex Reference and Tester
    url: https://regexr.com/
  - title: Online regex tester
    url: https://regex101.com/
related:
  - type: Actions
    name: ELSE
  - type: Actions
    name: ENDIF
---
The actions following this action will only be executed when the `<subject>` matches the `<pattern>`.

Optionally the whole match (or only a group specified by `[group]`) can be saved into `[&target]`.
