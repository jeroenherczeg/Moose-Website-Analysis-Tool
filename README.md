# Moose - Website Analysis Tool

Moose is a Website Analysis Tool built with node.js.

I want to have a tool that will analyse my work before giving it to the client. To make sure the website is optimalized and valid.
I would also like to use it to give a potential client an overview of their current website, to better plan a redesign.
Generating a PDF report that would easy be customized for other developers.

- [Status](#status)
- [Goals](#goals)
- [Tests](#tests)
- [Dependencies](#dependencies)
- [Contribute](#contribute)

## Status

*Still a dream ..*

## Goals

- Easy to use
  - Input: command [url] [-l X level of tests]
  - Output: PDF

## Tests

- Performance
  - Valid HTML
  - Valid CSS
  - Valid JavaScript
  - Page Speed
  - HTTP Requests
  - Assets Optimazed (Minification, compression, cache, ...)
- Layout
  - Screenshot extra small device *(phone portrait)*
  - Screenshot small device *(phone landscape - tablet portraid)*
  - Screenshot medium device *(tablet landscape - small desktop)*
  - Screenshot large device *(desktop)*

## Dependencies

The following Node Packages have been used and will be install automatically by npm.

- https://npmjs.org/package/yslow
- https://npmjs.org/package/crawler
- https://npmjs.org/package/jshint
- https://npmjs.org/~kangpangpang
- https://npmjs.org/package/heatmap
- https://npmjs.org/package/snipes
- https://npmjs.org/package/heifer
- https://npmjs.org/package/htmlhint
- https://npmjs.org/package/jscop
- https://npmjs.org/package/clicks

## Contribute
Contributions are welcome and much appreciated!
