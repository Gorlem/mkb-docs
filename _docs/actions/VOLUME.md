---
layout: docs
title: VOLUME
type: Actions
name: "VOLUME(<value>,[category])"
category: Settings
changelog:
  - type: Updated
    version: v0.10.4
    message: "Second parameter to specify the sound category"
  - type: Added
    version: v0.8.5
---
Sets the sound volume for the specified category.

`<value>` has to be between `0` and `100`.

`[category]` can be one of the following values:
* `"music"`
* `"master"`
* `"records"`
* `"weather"`
* `"blocks"`
* `"hostile"`
* `"neutral"`
* `"players"`
* `"ambient"`


