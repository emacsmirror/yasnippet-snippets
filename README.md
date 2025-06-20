# Yasnippet official snippet collections

[![MELPA Stable](https://stable.melpa.org/packages/yasnippet-snippets-badge.svg)](https://stable.melpa.org/#/yasnippet-snippets)
[![NonGNU ELPA](https://elpa.nongnu.org/nongnu/yasnippet-snippets.svg)](https://elpa.nongnu.org/nongnu/yasnippet-snippets.svg)
[![MELPA](https://melpa.org/packages/yasnippet-snippets-badge.svg)](https://melpa.org/#/yasnippet-snippets)

This repository contains the official collection of snippets for [yasnippet](http://github.com/capitaomorte/yasnippet).

You can see a generated table of all snippets [here](https://andreacrotti.pro/yasnippet-snippets/snippets).

# How to install

## From melpa

You can install this package from melpa, by first ensuring that you have the melpa source in your package-archives.

```lisp
(require 'package)
(add-to-list 'package-archives
             '("melpa" . "http://melpa.org/packages/") t)
(package-initialize)
```

Once that is done, then just refresh the packages and install it with.

* <kbd>M-x package-refresh-contents</kbd>
* <kbd>M-x package-install yasnippet-snippets</kbd>

Now all the snippets will load automatically, as soon as yasnippet loads.

## On Debian ≥10 and derivatives such as Ubuntu ≥ 18.10

`sudo apt install elpa-yasnippet-snippets`

# Contributing

If you have any useful snippets for any language or framework, then please feel free to contribute, by opening a PR or an issue if you have any suggestions.

To study the current snippets, I suggest that you use `M-x yas-describe-tables`,
which will show a table representation of all the snippets that are available in the current mode.


# Guidelines

Snippets need to be generic enough to be useful for everyone, and not contain anything specific to your own system.

# Various notes

## HTML snippets

Until September 1st 2014 there were a lot of HTML snippets in the repository, which sometimes were useful, but I came to the conclusion that yasnippet was not the right tool for them, so they were removed in this pull request:
https://github.com/AndreaCrotti/yasnippet-snippets/pull/49

To everyone writing a lot of HTML I suggest using [emmet mode](https://github.com/smihica/emmet-mode) instead, which is a much more powerful mode for writing HTML tags.
