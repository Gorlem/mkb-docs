---
layout: docs
title: CHATVISIBLE
type: Actions
name: "CHATVISIBLE(<value>)"
category: Settings
changelog:
  - type: Added
    version: v0.9.9
---
Set visibility of minecraft chat.

By default it toggles between Shown and Hidden.

Can be one of the following values:
* `"show"` or `0` for __Shown__
* `"commands"` or `1` for __Commands Only__
* `"hidden"` or `2` for __Hiddenn__

Returns the new visibility state.
