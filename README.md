# pureBuster

A [MathJax](http://www.mathjax.org) ready [Pure](http://purecss.io) based theme for [Ghost](http://github.com/tryghost/ghost/).
Freely inspired by [Pure Blog example layout](http://purecss.io/layouts/).

There are two main themes: dark and light. They can be switched changing the @import rule at the beginning of `assets/css/style.css`.
To change the colorsets and keep the theme structure is enough to copy either dark.css or light.css (they contains only colours information), modify it and redefine the import line with the appropriate name.

To set up google+, disqus or facebook comments is enough to open posts.hbs, uncomment the appropriate section at the end of the file and add the appropriate variables.

A running version of the dark theme is on my blog [Tales of a Fractal Spectrum](http://ghost.mseri.me).

## History

- 0.0.3 dark and light theme merged. 
- 0.0.2 added a Light theme version (branch light); added Google +, Disqus and Facebook comments (just enable the one you prefer uncommenting it in post.hbs)
- 0.0.1 first release

## Known problems

The social icons do not appear in google chrome. I am still working on a fix.

## Copyright & License

Copyright (C) 2013 Marcello Seri - Released under the MIT Lincense.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.