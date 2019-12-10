---
layout: docs
title: ACHIEVEMENTGET
type: Actions
name: "ACHIEVEMENTGET(<text>,[itemid[:damage]])"
category: GUI
hidden: true
changelog:
  - type: Deprecated
    version: v0.15.1
    message: "Preferred to use the action TOAST now"
  - type: Updated
    version: v0.15.1
    message: "Shows now an Advancement Toast"
  - type: Added
    version: v0.9.4
---
Displays an "Advancement made!" popup you get when completing an advancement with a custom message and optionally a custom item.

The successor is [TOAST]({{ site.baseurl }}{% link _docs/actions/TOAST.md %}) with the option to create other types of popups.

### Example
```
// With no item id; Shows an grass block
ACHIEVEMENTGET("Hello Grass")

// With an item id
ACHIEVEMENTGET("Hello Stone","stone")

// With an item id and metadata
ACHIEVEMENTGET("Hello Birch","log:2")
```
