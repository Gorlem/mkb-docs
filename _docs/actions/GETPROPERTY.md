---
layout: docs
title: GETPROPERTY
type: Actions
name: "GETPROPERTY(<control>,<property>)"
category: Mod related
changelog:
  - type: Added
    version: v0.11.3
---
Returns the value of the specified property from the specified GUI control


The following properties are available for each control:

 * __Button__
    * `"name"`
    * `"visible"`
    * `"hotkey"`
    * `"text"`
    * `"hide"`
    * `"sticky"`
    * `"colour"`
    * `"background"`
 * __Icon__
    * `"name"`
    * `"visible"`
    * `"align"`
    * `"scale"`
    * `"damage"`
    * `"background"`
 * __Label__
    * `"name"`
    * `"visible"`
    * `"align"`
    * `"text"`
    * `"binding"`
    * `"shadow"`
    * `"colour"`
    * `"background"`
 * __Custom Gui__
    * `"name"`
    * `"visible"`
    * `"layout"`
    * `"width"`
    * `"heigth"`
 * __Playback Status__
    * `"name"`
    * `"visible"`
 * __Progress Bar__
    * `"name"`
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
    * `"name"`
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
    * `"name"`
    * `"visible"`
    * `"lifespan"`
    * `"colour"`
