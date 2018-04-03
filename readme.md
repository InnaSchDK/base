# [Base](http://getbase.org)

### A Rock Solid, Responsive CSS Framework built to work on all devices big and small.

#### Lightweight and minimal code. Spend less time overriding styles and focus more time on creating beautiful website applications.

[![Travis Build Status][travis-img]][travis] [![David Dependencies Status][david-img]][david]

[travis-img]:   https://img.shields.io/travis/getbase/base.svg?branch=master
[david-img]:    https://img.shields.io/david/dev/getbase/base.svg?branch=master&label=dependencies
[travis]:       https://travis-ci.org/getbase/base
[david]:        https://david-dm.org/getbase/base?type=dev

* * *

## Table of contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Documentation](#documentation)
- [Demo](#demo)
- [Modules and Components](#modules-and-components)
- [Support](#support)
- [Credits](#credits)
- [Authors](#authors)

## Introduction
Base itself is a very thin layer which includes normalize.css and a few mixins to get you started.

You can then include what you need on top of Base such as typography, grids, individual components, etc to make it yours.

## Installation
If you are creating a new project from scratch, it is highly recommended you [use the base starter template](https://github.com/getbase/starter).

```bash
git clone https://github.com/getbase/starter.git \
new-website && cd new-website && rm -rf .git
npm install && npm start
```

Alternatively, if you have an existing project, simply install base using [NPM](https://www.npmjs.com/):

```bash
npm install --save @getbase/base
```

Once you have Base installed, you can then build on top of it by including your own styles or add the ready made packages provided by Base:

### Import via CSS file:
  ```html
    <link rel="stylesheet" href="https://cdn.rawgit.com/getbase/base/master/css/index.css">
  ```

  OR

  ```css
    @import ("https://cdn.rawgit.com/getbase/base/master/css/index.css")
  ```

### Import via SCSS file:

  ```scss
  /* Import Base */
  @import "node_modules/@getbase/base/scss/index";

  /* Import Base Typography Module */
  @import "node_modules/@getbase/typography/scss/index";

  /* Your Custom Website/App Styles */
  @import "main"
  ```


### Import via LESS file:

  ```css
  /* Import Base */
  @import "node_modules/@getbase/base/scss/index";

  /* Import Base Typography Module */
  @import "node_modules/@getbase/typography/scss/index";

  /* Your Custom Website/App Styles */
  @import "main"
  ```

* * *

## Documentation
...

* * *

## Demo
...

* * *

## Modules and Components
...

* * *

## Support
* IE10+ and all other modern browsers.
* Please, specify browsers you need to support in `package.json` according to [browserslist docs](https://github.com/ai/browserslist#queries).

* * *

## Credits
- Thanks to [Nicolas Gallagher (@necolas)](https://github.com/necolas/) for normalize.css

* * *
## License
[MIT Open Source](https://opensource.org/licenses/MIT)

* * *

## Authors
- [Matthew Hartman](https://twitter.com/matthewhartmans)
