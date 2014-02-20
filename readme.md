*This repository is a mirror of the [component](http://component.io) module [ramitos/rating](http://github.com/ramitos/rating). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-rating`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# rating

rating widget. [demo](http://ramitos.github.com/rating)

## install

```bash
$ component install ramitos/rating
```

## example

```js
var rating = require('rating');

rating(function (el) {
  document.getElementById('rating').appendChild(el)
});
```

## api

#### rating(callback)

`callback` arguments:
 * DOMElement

returns a new rating instance

#### instance()

returns the current rating number

#### instance.disable()

#### instance.enable()

## license

MIT