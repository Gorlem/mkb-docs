---
layout: docs
title: SHADERGROUP
type: Actions
name: "SHADERGROUP([path])"
category: Settings
changelog:
  - type: Updated
    version: v0.11.3
    message: "Use `\"-\"` to step backwards through shaders"
  - type: Added
    version: v0.10.4
---
Sets the active shader group to the shader matching path

Can be one of the following shaders:

* `"spider"`
* `"outline"`
* `"desaturate"`
* `"wobble"`
* `"scan_pincushion"`
* `"ntsc"`
* `"creeper"`
* `"color_convolve"`
* `"blur"`
* `"bits"`
* `"blobs2"`
* `"flip"`
* `"invert"`
* `"notch"`
* `"antialias"`
* `"entity_outline"`
* `"bumpy"`
* `"sobel"`
* `"art"`
* `"blobs"`
* `"fxaa"`
* `"pencil"`
* `"phosphor"`
* `"deconverge"`
* `"green"`

You can also use `"+"` or `"-"` to toggle between shaders.

Returns the name of the selected shader.
