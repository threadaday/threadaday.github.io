# Thread A Day

The official [Thread A Day](http://threadaday.github.io) website.

# About

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