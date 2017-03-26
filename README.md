# Emerald

[![dependency Status](https://david-dm.org/visionappscz/emerald/status.svg)](https://david-dm.org/visionappscz/emerald)
[![devDependency Status](https://david-dm.org/visionappscz/emerald/dev-status.svg)](https://david-dm.org/visionappscz/emerald?type=dev)
[![Build Status](https://travis-ci.org/visionappscz/emerald.svg?branch=master)](https://travis-ci.org/visionappscz/emerald)

[VisionApps'](https://github.com/visionappscz) fork of
[lmc-eu.github.io/emerald/](http://lmc-eu.github.io/emerald/), refactored to flexbox.

Emerald is a pragmatic responsive grid system in LESS.

* Responsive
* OOCSS
* BEM sytax
* Nestable
* Mobile-first
* Tablet-come-from
* Flexbox based
* (= no floats, clears or rows)
* Configurable

## How to use

Either include source *LESS* files into your project (recommended) or use compiled *CSS*.

```less
// main.less
@import "emerald/less/emerald";
```

## Browser support

Emerald grid system is tested in the latest versions of the major browsers on the major desktop and mobile platforms.

### Support for `vw` units
Android browser does not support `vw` units. Load `emerald.js` at the
bottom of the page:

```html
<script src="js/emerald.js"></script>
```

### Internet Explorer 8
Legacy browser are supported by [grunt-legacssy](https://github.com/robinpokorny/grunt-legacssy).

## The name
Please note that the name *Emerald* does not refer to the gemstone of that name but to a [diamond cut](http://www.lumeradiamonds.com/diamond-education/emerald-cut-diamond) *"originally developed for the cutting of emeralds."*

Does it really matter? No.

## Credit

This grid system was inspired by:

* [csswizardry/csswizardry-grids](http://github.com/csswizardry/csswizardry-grids)
* [twbs/bootstrap](http://github.com/twbs/bootstrap)
* [yui/pure](http://github.com/yui/pure)

## Changelog
* v2.0.0    Refactor grid to flexbox
* v1.2.1    Fix `.e-0` classes (fixes [#4](https://github.com/lmc-eu/emerald/issues/4))
* v1.2.0    Code refactoring, fix typos, remove legacy and minimised CSSs
* v1.1.3    Fix a bug with .e-0 classes overwriting on higher devices
* v1.1.2    Fix a printing problem in FF
* v1.1.1    Hiding .grid__item in print
* v1.1.0    Add print styles (fixes [#6](https://github.com/lmc-eu/emerald/issues/6))
* v1.0.0    Initial release, production ready
