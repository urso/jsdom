Introduction
============
JSDom provides DOM like classes, thus it's possible to parse and manipulate
HTML Documents in browsers and/or on server side the very same way one is used
to.
Additionally It's a relative simple task to adjust JavaScript Template
frameworks (for Example PURE 2 with slight modifications was used by the
author) to use JSDom, so they can be easily used in environments (e.g. on
server side) without native DOM support.

Usage
=====

All needed sources are available in the "src" directory.

You can parse an HTML file to a JSDom object (or an Array of DOM elements,
depending on input data) using *parseDom(\<String\>)*. The JSDom Elements
support a quite extensive subset of the DOM functionality supported by most
browsers. If the JavaScript engine supports setters/getters the same way
Firefox does even innerHTML, innerText functionality will work, otherwise one
has to use setInnerHTML/getInnerHTML, setInnerText/getInnerText respectively.

Credits
========

- JavaScript HTML Parser:  
  HTML Parser By John Resig (ejohn.org)
  Original code by Erik Arvidsson, Mozilla Public License
  http://erik.eae.net/simplehtmlparser/simplehtmlparser.js

