rss-bridge
===

rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one.

Supported sites/pages (main)
===

 * `YouTube` : YouTube user channel, playlist or search

Output format
===
Output format can take several forms:

 * `Atom` : ATOM Feed, for use in RSS/Feed readers
 * `Json` : Json, for consumption by other applications.
 * `Html` : Simple html page.
 * `Plaintext` : raw text (php object, as returned by print_r)
   

Requirements
===

 * PHP 5.4
 * `openssl` extension enabled in PHP config (`php.ini`)

Enabling/Disabling bridges
===

By default, the script creates `whitelist.txt` and adds the main bridges (see above). `whitelist.txt` is ignored by git, you can edit it:
 * to enable extra bridges (one bridge per line)
 * to disable main bridges (remove the line)

New bridges are disabled by default, so make sure to check regularly what's new and whitelist what you want!

[![Deploy on Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy?source=https://github.com/idir0609/rssyoutube)

License
===
Code is [Public Domain](UNLICENSE).

Including `PHP Simple HTML DOM Parser` under the [MIT License](http://opensource.org/licenses/MIT)

