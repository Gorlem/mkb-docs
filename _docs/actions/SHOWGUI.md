---
layout: docs
title: SHOWGUI
type: Actions
name: "SHOWGUI(<screen>,[esc_screen],[macro_keys])"
category: Mod related
changelog:
  - type: Fixed
    version: v0.14.1
    message: "Was previously not closing current custom screen when called with no arguments"
  - type: Updated
    version: v0.14.1
    message: "Third argument to allow macro keys to still function when a custom GUI is displayed"
  - type: Updated
    version: v0.12.1
    message: "Now creates the screen if it doesn't exist yet"
  - type: Added
    version: v0.9.9
---
Show a custom gui screen, creates it if it doesn't exist.

Set `[macro_keys]` to `true` when macro keys should still work.
