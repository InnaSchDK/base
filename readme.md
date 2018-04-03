d# [Base](http://getbase.org)

### A Rock Solid, Responsive CSS Framework built to work on all devices big and small.

Lightweight and minimal code. Spend less time overriding styles and focus more time on creating beautiful website applications.

[![Travis Build Status][travis-img]][travis] [![David Dependencies Status][david-img]][david]

[travis-img]:   https://img.shields.io/travis/getbase/base.svg?branch=master
[david-img]:    https://img.shields.io/david/dev/getbase/base.svg?branch=master&label=dependencies
[travis]:       https://travis-ci.org/getbase/base
[david]:        https://david-dm.org/getbase/base?type=dev

* * *

## Table of contents

* [Introduction](#introduction)
* [Installation](#installation)
* [Documentation](#documentation)
* [Demo](#demo)
* [Modules and Components](#modules-and-components)
* [Support](#support)
* [Authors](#authors)
* [Credits](#credits)

* * *

## Introduction
Base itself is a very thin layer which includes Normalize.css and a few mixins to get you started.

You can then include what you need on top of Base such as typography, grids, individual components, etc to make it yours.

* * *

## Installation
If you are creating a new project from scratch, it is highly recommended you [use the base starter template](https://github.com/getbase/starter).

```bash
git clone https://github.com/getbase/starter.git \
new-website && cd new-website && rm -rf .git
npm install && npm start
```

For existing projects, simply install base using [NPM](https://www.npmjs.com/):

```bash
npm install --save @getbase/base
```

Once you have Base installed, you can build on top of it by including your own custom styles or add the [ready made modules](#modules-and-components)

#### CSS Import:
  ```css
  import url("https://cdn.rawgit.com/getbase/base/master/css/index.css");
  ```

#### SCSS Import:

  ```scss
  /* Import Base */
  @import "node_modules/@getbase/base/scss/index";
  /* Your Custom Website/App Styles */
  @import "main"
  ```


#### LESS Import:

  ```css
  /* Import Base */
  @import "node_modules/@getbase/base/scss/index";
  /* Your Custom Website/App Styles */
  @import "main"
  ```

* * *

## Documentation
Base includes the latest version of Normalize.css by default and includes a few Mixins to get you started.


### SCSS

| Mixin | Purpose | Example | Outcome |
| ----- | ------- | ------- | ------- |
| `@include breakpoint(x)` | Apply a breakpoint for a particular device. Accepts values m, l and xl (m: medium, l: large, xl: extra large)  | `.box { @include breakpoint(m) { ... } }` | Applies styles to .box for medium devices and up |
| `@include background-alpha(hex, percentage)` | Applies a background color with opacity | `@include background-alpha(#000, 50%)` | Applies a background color of black with opacity set to 50% |
| `@include animation(time)` | Applies animation speed | `@include animation(2s)` | Animation will run for 2 seconds |

### LESS

| Mixin | Purpose | Example | Outcome |
| ----- | ------- | ------- | ------- |
| `.background-alpha(hex, percentage)` | Applies a background color with opacity | `.background-alpha(#000, 50%)` | Applies a background color of black with opacity set to 50% |
| `.animation(time)` | Applies animation speed | `.animation(2s)` | Animation will run for 2 seconds |

* * *

## Demo
...

* * *

## Modules and Components

* [Typography](#typography)
* [Typography Helpers](#typography-helpers)
* [Tables](#tables)
* [Animations](#animations)
* [Layout Helpers](#layout-helpers)
* [Containers](#containers)
* [Grid](#grid)
* [Grid Helpers](#grid-helpers)
* [Grid Non Responsive](#grid-non-responsive)
* [Grid (Legacy)](#grid-legacy)
* [Grid Helpers (Legacy)](#grid-helpers-legacy)
* [Grid Non Responsive (Legacy)](#grid-non-responsive-legacy)
* [Buttons](#buttons)

...

* * *

## Support
* IE10+ and all other modern browsers.
* Please, specify browsers you need to support in `package.json` according to [browserslist docs](https://github.com/ai/browserslist#queries).

* * *

## Credits
* Thanks to [Nicolas Gallagher (@necolas)](https://github.com/necolas/) for Normalize.css

* * *

## Authors
#### Matthew Hartman
* [https://twitter.com/matthewhartmans](https://twitter.com/matthewhartmans)
* [https://github.com/matthewhartman](https://github.com/matthewhartman)

* * *

## License
Code released under the [MIT Open Source](https://opensource.org/licenses/MIT) license.