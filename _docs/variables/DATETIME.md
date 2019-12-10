---
layout: docs
title: DATETIME
type: Variables
name: "%DATETIME%"
category: Time and Date
changelog:
  - type: Added
    version: v0.9.1
links:
  - title: Date Formatting
    url: https://docs.oracle.com/javase/7/docs/api/java/text/SimpleDateFormat.html
---
Current date and time in the format "year-month-day hour:minute:second"

### Example
```
// %DATETIME% is the same as
TIME(&datetime,"yy-MM-dd hh:mm:ss")
```
