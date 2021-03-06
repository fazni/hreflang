ALTERNATE HREFLANG
======================

Search engines use <link rel="alternate" hreflang="x" /> tags to serve the
correct language or regional URL in search results.

Alternate hreflang is a simple module that automatically adds these tags to your
pages. It has no dependencies, but works well with Entity Translation module.

More info about hreflang can be found at the article "Use hreflang for language
and regional URLs": https://support.google.com/webmasters/answer/189077

A few days after installing this module, you should see a message reading
"Currently, your site has no hreflang tag errors" at Google Webmaster Tools:
https://www.google.com/webmasters/tools/i18n

If for some reason you'd like to modify the hreflang tags on a page, you can do
so by implementing the core hook_language_switch_links_alter() or
hook_html_head_alter() hooks in a custom module.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/hreflang/issues

Current Maintainers
-------------------

- Said El fazni (https://github.com/fazni/)


Credits
-------

- Ported to Backdrop CMS by Said El fazni (https://github.com/fazni).
- Originally written for Drupal by Mark burdett (https://github.com/mfb).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
