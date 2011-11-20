Shortcut.io is an open source software to build a bookmarking service.

[![Flattr Shortcut.io](http://api.flattr.com/button/flattr-badge-large.png)](http://flattr.com/thing/438691/Shortcut-io-Bookmarking)

## Background

Early 2011 I have started to build my own bookmarking service as I was unsatisfied
with the existings ones. While it is trivial to store bookmarks with any service
it was much harder to ever find a certain bookmark again once you have 1000+ of
them. Shortcut.io has the goal to make finding bookmarks as easy as storing them.
Then, when I got done about 60-70% of the initial public release I started working
for a new company and had not enough time to continue working on it. Now, many
months later I have realized that I will not finish it any time soon and that
there are already enough comercial bookmarking services. Therefor it would be
a complete waste of time if I would let this project die without any benefit for
anybody. This is why I have decided to open source it.

The service is up and running on http://shortcut.io and can be use free of charge.
Either people will like it, contribute to it and maybe even install it on their
own or it will just fade away. Personally I would be extremely happy if it evolves
into a nice little community driven project.

So if you care to get involved write me a message - I will help you getting it
to run.

## Features

* Slim and fast interface driven by [backbone.js](http://documentcloud.github.com/backbone/)
* Fast and flexible search powered by [elasticsearch](http://www.elasticsearch.org/)
* Visual bookmark thumbnails generated asynchronously
* Import and export of bookmarks from other services / to other services via common file format
* Easy to use Bookmarklet

## Screenshot

![Shortcut.io Screenshot](http://smyck.org/shortcutio.jpg)

## Unfinished Features / Ideas

* Discover / browse bookmarks from friends
* Smart folders based on search terms / tags
* Ad-hoc collections for web research ( say you're looking for a new gadget or appartment and save all related bookmarks in a special collection)
* Public bookmarks
* Improved Elasticsearch indeces
* Browse by tags
* Browse by timeline
* Advanced search
* Polished UI
* Replace wkhtmltoimage with phantom.js as they have fixed all issues I filed in the meantime
* Tests frontend / backend
* Chrome / Safari / FF Extensions
…

## Dependencies

* Ruby / Rails
* SQLite / MySQL / Postgres
* Redis
* wkhtmltoimage

## License

Copyright (C) 2011 by John-Paul Bader

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.