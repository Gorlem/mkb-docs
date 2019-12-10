---
layout: docs
title: TOAST
type: Actions
name: "TOAST([type],[icon],[text1],[text2],[ticks])"
category: GUI
changelog:
  - type: Added
    version: v0.15.1
links:
  - title: TOAST Explanation
    url: http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1275039-macro-keybind-mod?comment=16787
  - title: Item ID Overview
    url: https://www.minecraftinfo.com/idnamelist.htm
---
Displays an user-defined toast.

The following toasts are possible:

 * __Advancement Toast__ ("Advancement made!")
   * `[type]` should be `"advancement"`
   * `[icon]` can be any item name
   * `[text1]` will be displayed
 * __Challenge Toast__ ("Challenge complete!")
   * `[type]` should be `"challenge"`
   * `[icon]` can be any item name
   * `[text1]` will be displayed
 * __Goal Toast__ ("Goal reached!")
   * `[type]` should be `"goal"`
   * `[icon]` can be any item name
   * `[text1]` will be displayed
 * __Recipe Toast__ ("New Recipes Unlocked!")
   * `[type]` should be `"recipe"`
   * `[icon]` can be any item name
   * No text will be displayed
 * __Tutorial Toast__
   * `[type]` should be `"tutorial"`
   * `[icon]` can be one of the following values
       * `"keys"`
       * `"mouse"`
       * `"tree"`
       * `"recipe_block"`
       * `"planks"`
   * `[text1]` and `[text2]` will be displayed
   * `[ticks]` specifies how long the toast will be displayed
 * __System Hint Toast__
   * `[type]` should be `"hint"`
   * `[icon]` should be empty
   * `[text1]` and `[text2]` will be displayed
 * __System Narrator Toast__
   * `[type]` should be `"narrator"`
   * `[icon]` should be empty
   * `[text1]` and `[text2]` will be displayed
 * __Remove user-defined tutorial toasts__
   * `[type]` should be `"clear"`
   * if `[icon]` is `"all"` vanilla toast will also be removed
