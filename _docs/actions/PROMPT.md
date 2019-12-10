---
layout: docs
title: PROMPT
type: Actions
name: "PROMPT(<&target>,<paramstring>,[prompt],[override],[default])"
category: Mod related
changelog:
  - type: Updated
    version: v0.9.7
    message: "New fifth parameter"
  - type: Added
    version: v0.9.5
---
Displays a prompt (or prompts) by parsing the params in paramstring.

Returns the result.

### Example
```
PROMPT(&targetvar,"$$u","Prompt message",true);
```
