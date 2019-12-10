---
layout: docs
title: MATCH
type: Actions
name: "MATCH(<subject>,<pattern>,[&target],[group],[default])"
category: Calculations
changelog:
  - type: Updated
    version: v0.9.0
    message: "Can now store mutliple matches in multiple variables"
  - type: Updated
    version: v0.8.7
    message: "New fifth parameter to specify default value if the match fails"
  - type: Added
    version: v0.8.6
links:
  - title: Regular Expressions QuickStart
    url: http://www.regular-expressions.info/quickstart.html
  - title: Online regex tester
    url: https://regex101.com/
  - title: Regex Reference and Tester
    url: https://regexr.com/
---
Runs a regular expression match on the `<subject>` and puts the result in `<&target>`.

Returns the matched groups as an array.

Alternative Syntax;
```
MATCH(<subject>,<pattern>,{&target1,&target2,&target3})
MATCH(<subject>,<pattern>,&target[])
```

### Example
```
&input = "Hello World!!"
&regex = "(Hello) (World)"

MATCH(%&input%,%&regex%,&match)
// &match now contains the whole match "Hello World"

MATCH(%&input%,%&regex%,&match,2)
// &match now contains only the second group "World"

MATCH("no match",%&regex%,&match,1,"default")
// &match now contains the default value "default", since the regex couldn't match the input

MATCH(%&input%,%&regex%,{&hello,&world})
// &hello and &world now contain the first and second group

&groups[] = MATCH(%&input%,%&regex%)
// &groups[] now contains the whole match and the two groups
```
