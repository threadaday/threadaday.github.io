# Thread A Day

The official [Thread A Day](http://threadaday.github.io) website.

## What is this?

Thread A Day is a site that aims to provide meaningful discussion around one link or topic each day.

### What a great idea! I'm sure you came up with it yourself.

Nope! It was inspired by [this post](https://news.ycombinator.com/item?id=7617434) from Hacker News.

---

# Contributing

## Dependencies

- Gulp (`npm install -g gulp`)
- Bower (`npm install -g bower`)
- Jekyll (`gem install jekyll`)

## Instructions

To build the site:

`sh install.sh`

---

To actively develop:

```bash

gulp
# Open a new terminal tab for Jekyll
jekyll serve --watch
google-chrome http://localhost:4000

```

---

To package the site for deployment:

```bash

gulp build
jekyll build

```

# License

Copyright (c) 2014, Duncan Smith

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.