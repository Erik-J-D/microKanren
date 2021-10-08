# µKanren - Racket Edition

This is a fork of the original microKanren code provided by Jason Hemann and Daniel P. Friedman, modified to run in a modern (v8.2) version of Racket since I couldn't figure out which interpreter they used and the few I tried failed to run all the tests successfully.

## Changes in this fork

- Rename everything to .rkt
- add `provide` and `require` expressions to sort out imports for Racket
- add an `assp` definition since the built in one in the lists library didn't quite work

The tests all pass in Racket v8.2.

## Original Copyright Notice

Copyright (C) 2013 Jason Hemann and Daniel P. Friedman

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
