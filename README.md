Jasmine-Runner
==============

HTML runner for Jasmine compatible with Test::WWW::Jasmine
enhancements.

Jasmine Gem or Perl module Test::WWW::Jasmine solves the problem of
JavaScript test automation; however the mess usually associated with
running Jasmine specs in local browser remains: lots of HTML files,
each one needs to be kept in sync with Jasmine updates, specs going
astray, etc.

This HTML runner tries to provide the answer. It supports all
Test::WWW::Jasmine syntax sugar so you won't have to keep two copies of
test spec for manual and automated testing. It takes the same specs
and runs them in a browser of your choice, what can be easier than that?

It does not require installation, but take a look inside test.html
and customize URLs if you feel like it. Otherwise, just drop the whole
bunch of files into /test/ directory on your HTTP server and try opening
it: http://yourserver.com/test/test.html?01_sample.js

Tested in:

- MSIE 6+
- Chrome 6+
- Firefox 3.6+
- Opera 11
- Safari 4+

Version 0.99.

This extension is released under GPL 3.0 license.

Commercial use is permitted to the extent that the code/component(s) do
NOT become part of another Open Source or Commercially licensed development
library or toolkit without explicit permission.

Copyright (c) 2011-2012 by Alexander Tokarev, <nohuhu@nohuhu.org>.
Special thanks to IntelliSurvey, Inc. for sponsoring my work on this code.
