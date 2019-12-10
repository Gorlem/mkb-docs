---
layout: docs
title: SETPROPERTY
type: Actions
name: "SETPROPERTY(<control>,<property>,<value>)"
category: Mod related
changelog:
  - type: Updated
    version: v0.14.1
    message: "Added icon control"
  - type: Added
    version: v0.9.9
---
Sets the value of the specified property on the specified GUI control

The following properties are available for each control:

 * __Button__
    * `"visible"`
    * `"hotkey"`
    * `"text"`
    * `"hide"`
    * `"sticky"`
    * `"colour"`
    * `"background"`
 * __Icon__
    * `"visible"`
    * `"align"`
    * `"scale"`
    * `"damage"`
    * `"background"`
 * __Label__
    * `"visible"`
    * `"align"`
    * `"text"`
    * `"binding"`
    * `"shadow"`
    * `"colour"`
    * `"background"`
 * __Custom Gui__
    * `"visible"`
    * `"layout"`
    * `"width"`
    * `"heigth"`
 * __Playback Status__
    * `"visible"`
 * __Progress Bar__
    * `"visible"`
    * `"expression"`
    * `"style"`
    * `"min"`
    * `"max"`
    * `"calcmin"`
    * `"calcmax"`
    * `"colour"`
    * `"background"`
 * __Slider__
    * `"visible"`
    * `"binding"`
    * `"hotkeydec"`
    * `"hotkeyinc"`
    * `"min"`
    * `"max"`
    * `"calcmin"`
    * `"calcmax"`
    * `"colour"`
    * `"background"`
 * __Textarea__
    * `"visible"`
    * `"lifespan"`
    * `"colour"`
