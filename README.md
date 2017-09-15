# Can I use?

## Goog library

We should stop using goog.library and migrate all current code to plain JS.
Exceptions: goog.require, goog.module, goog.provide, goog.asserts*


## OpenLayers polyfills

We should stop using ol polyfills and migrate all current code to plain JS. The
GCC compiler (or babel transpiler) should inject the required mainstream polyfills automatically.
