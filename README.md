zepto-full
==========

This is a shim repository for [Zepto.js](http://zeptojs.com/) with all the available modules built within it.

# Installation

For use with Bower, simply run `bower install zepto-full` within your terminal.

# Build

This shim can be built by checking out the Zepto source, then-- within the root of that directory-- run the following commands:

```shell
  setenv MODULES 'zepto event ajax form ie detect fx fx_methods assets data deferred callbacks selector touch gesture stack ios3'
  npm run-script dist
```
