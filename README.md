ezflix
======

[![NPM version](https://badge.fury.io/js/ezflix.svg)](http://badge.fury.io/js/ezflix)
[![Build Status](https://travis-ci.org/Munter/ezflix.svg?branch=master)](https://travis-ci.org/Munter/ezflix)
[![Coverage Status](https://img.shields.io/coveralls/Munter/ezflix.svg?style=flat)](https://coveralls.io/r/Munter/ezflix?branch=master)
[![Dependency Status](https://david-dm.org/Munter/ezflix.svg)](https://david-dm.org/Munter/ezflix)

Play a video from an eztv torrent directly in your preferred media player.

ezflix combines the query syntax of [eztv-query](https://github.com/Munter/eztv-query) with the video playing capabilities of [peerflix](https://github.com/mafintosh/peerflix). Option arguments are passed to peerflix while non-option arguments are passed to eztv-query.

Installation and usage
----------------------
```
npm install -g Munter/ezflix
ezflix latest big bang theory -m
```

For peerflix options help: `ezflix -h`.

For more details on how to find what you are looking for, consult the [eztv-query README](https://github.com/Munter/eztv-query#query-syntax).

License
-------
(The MIT License)

Copyright (c) 2014 Peter Müller <munter@fumle.dk>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
