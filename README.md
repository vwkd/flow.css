# flow.css

A modern CSS Flow Layout



## Introduction

This style sheet implements Flow Layout. This is useful for showing flowing text, when no browser default style sheet is present or it was unset like after using [reset.css](https://github.com/vwkd/reset.css).

It's basically the browser default style sheet, but only with styles relevant for modern elements. Also with improved values.

It supports only basic HTML elements like those generated from Markdown. It uses `<article>` elements as a container for such flowing text.



## Demo

See the test page [with reset and flow](test.html) and [without reset](testbaseline.html). Thanks to [html5-test-page](https://github.com/cbracco/html5-test-page).



## Features

- Flow Layout within the `<article>` element
- `display: flow-root` instead of `display: flow`
- all formatting elements
- bigger headers with smaller margins
- lists with consisten marker style and child lists without margin
- blockquote without color
- table without color and alignment

Beware: Don't use the `<article>` element for anything else than flowing text.



## Browser support

This reset should work in all modern browsers.

For more details, see browser support for [`:is()` pseudo-class](https://caniuse.com/css-matches-pseudo).