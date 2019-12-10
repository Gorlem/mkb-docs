---
layout: docs
title: $$<file.txt>
type: Parameters
name: "$$<file.txt>"
changelog:
  - type: Added
    version: v0.2.0
---
Includes the content of the file directly into the current macro.

One macro can only contain up to ten includes, everyone after that gets ignored.
In case you need a higher limit you have the ability to increase it from the config file.
The config file is in `.minecraft/liteconfig/common/macros/.macros.txt`. There you have to change the compiler.maxinclude property.
