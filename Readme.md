# dotsplit.js

[![Build Status](https://travis-ci.org/wilmoore/dotsplit.js.png?branch=master)](https://travis-ci.org/wilmoore/dotsplit.js)
[![Build Status](https://david-dm.org/wilmoore/dotsplit.js.png)](https://david-dm.org/wilmoore/dotsplit.js)
[![NPM version](https://badge.fury.io/js/dotsplit.js.png)](http://badge.fury.io/js/dotsplit.js)

  Transform dot (`.`) delimited strings to array of strings for [Node.js][] and the browser.

## Examples

    dotsplit('group.0.section.a.seat.3')
    //=> ['group', '0', 'section', 'a', 'seat', '3']

    dotsplit('01.document\.png')
    //=> ['01', 'document.png']

## Installation

[component](http://component.io/wilmoore/dotsplit.js)

    $ component install wilmoore/dotsplit.js

[bower](http://sindresorhus.com/bower-components/)

    $ bower install dotsplit.js

[npm](https://npmjs.org/package/dotsplit.js)

[![NPM](https://nodei.co/npm/dotsplit.png?downloads=true)](https://nodei.co/npm/dotsplit/)

[jam](http://jamjs.org/packages/#/details/dotsplit.js)

    $ jam install dotsplit.js

[volo](http://volojs.org)

    $ volo add wilmoore/dotsplit.js

[global][]

    <script src="https://raw.github.com/wilmoore/dotsplit.js/master/dotsplit.js"></script>

## Inspiration

- [selectn][]

## License

  MIT

[selectn]:  https://github.com/wilmoore/selectn
[global]:   https://raw.github.com/wilmoore/dotsplit.js/master/dotsplit.min.js
[Node.js]:  http://nodejs.org
