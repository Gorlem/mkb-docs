---
layout: docs
title: RUN
type: Commands
name: "RUN <file.txt> [arg1] [arg2] [args...]"
changelog:
  - type: Updated
    version: v0.15.1
    message: "dot as alias in REPL"
  - type: Updated
    version: v0.15.1
    message: "Autocompletion for filenames"
  - type: Added
    version: v0.14.1
---
Runs the specified script synchronously. Args are provided to the target script in the same manner as EXEC (eg. params $$[1], $$[2].. etc)
