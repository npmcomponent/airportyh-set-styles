*This repository is a mirror of the [component](http://component.io) module [airportyh/set-styles](http://github.com/airportyh/set-styles). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/airportyh-set-styles`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
set-styles
==========

Batch-set CSS properties on an element.

## Install

Install `set-styles` from npm or `airportyh/set-styles` from component.

## Usage

```js
var setStyles = require('set-styles')

setStyles(element, {
  position: 'absolute',
  top: 100 + 'px',
  left: 200 + 'px',
  width: 200 + 'px',
  height: 200 + 'px'
})
```