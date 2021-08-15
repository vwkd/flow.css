# flow.css

A modern CSS Flow Layout



## Introduction

This style sheet implements Flow Layout. This is useful for showing flowing text, when no browser default style sheet is present or it was unset like after using [reset.css](https://github.com/vwkd/reset.css).

It's basically the browser default style sheet, but only the section for text containing elements and with slightly different values. It is designed to work with the text containing elements generated from basic Markdown.



## Demo

See the test page [with reset and flow](test.html) and [without reset](testbaseline.html). Thanks to [html5-test-page](https://github.com/cbracco/html5-test-page).



## Features

- Flow Layout within the `<article>` element
- `display: flow-root` instead of `display: flow`
- bigger headers with smaller margins
- lists with consistent marker style, child lists without margin
- blockquote without color
- table without color and without alignment
- `font-size` on the `<article>` allows to scale size of contents since everything is in `em`

Beware: Using flow.css you shouldn't use `<article>` element for anything else than flowing text anymore!



## Browser support

This reset should work in all modern browsers.

For more details, see browser support for [`:is()` pseudo-class](https://caniuse.com/css-matches-pseudo).