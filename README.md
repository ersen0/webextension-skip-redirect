[![Build Status](https://travis-ci.org/sblask/firefox-skip-redirect.svg?branch=master)](https://travis-ci.org/sblask/firefox-skip-redirect)

firefox-skip-redirect
=====================
Some web pages use intermediary pages before redirecting to a final page. This
add-on tries to extract the final url from the intermediary url and goes there
straight away if successful. As an example, try this url:

 - www.google.com/chrome/?i-would-rather-use-firefox=http%3A%2F%2Fwww.mozilla.org/

Please give feedback(see below) if you find websites where this fails or where
you get redirected in a weird way when this add-on is enabled but not when it's
disabled.

See the add-on's preferences (also available by clicking the toolbar icon) for
options.

Feedback
--------

You can report bugs or make feature requests on
[Github](https://github.com/sblask/firefox-skip-redirect).

Patches are welcome.
