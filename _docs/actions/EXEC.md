---
layout: docs
title: EXEC
type: Actions
name: "EXEC(<file.txt>,[taskname],[params],...)"
category: Mod related
changelog:
  - type: Fixed
    version: v0.14.1
    message: "EXEC parameter requests leaked into macros using PROMPT"
  - type: Fixed
    version: v0.14.1
    message: "Arguments can now be accessed as variables with the correct type"
  - type: Fixed
    version: v0.9.0
    message: "Parses the parameters correctly"
  - type: Added
    version: v0.8.5
---
Creates a task by running the specified script file.

The params will be provided to the script as either variables (`&var1`, `&var2`, `&var3`, ...) or parameters (`$$[1]`, `$$[2]`, `$$[3]`, ...).
