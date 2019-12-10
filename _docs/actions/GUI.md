---
layout: docs
title: GUI
type: Actions
name: "GUI([name])"
category: GUI
changelog:
  - type: Updated
    version: v0.14.1
    message: "New possible value `\"repl\"`"
  - type: Fixed
    version: v0.10.12
    message: "Was not actually closing containers"
  - type: Updated
    version: v0.9.8
    message: "New possible values `\"macroplayback\"` and `\"texteditor\"`"
  - type: Added
    version: v0.5.0
---
Show (or hide) a gui screen

Possible values:
* `"chat"`
* `"filterablechat"`
* `"menu"`
* `"inventory"`
* `"options"`
* `"video"`
* `"controls"`
* `"macrobind"`
* `"macroplayback"`
* `"macroconfig"`
* `"texteditor"`
* `"repl"`

If no name is specified it will close the currently open gui.
