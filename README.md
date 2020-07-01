# Livedown
*Originally based on [shive/linedown](https://github.com/shime/livedown) with improvements.*

## Overview

Easily render markdown documents using the command line (CLI) based on the next generation markdown parser in javascript, with pluggable syntax [Markdown it!](https://github.com/markdown-it)

* Follows the [CommonMark spec](http://spec.commonmark.org/) + adds syntax extensions & sugar (URL autolinking, typographer).
* Configurable syntax! You can add new rules and even replace existing ones.
* High speed.
* [Safe](https://github.com/markdown-it/markdown-it/tree/master/docs/security.md) by default.
* Community-written plugins and other packages on npm.

### View the [Live Demo](https://markdown-it.github.io) to try it out or check out the screen capture below.
### ![](https://twobucks.co/assets/livedown.gif)

[![Build Status](https://travis-ci.com/billyromano/livedown2.svg?branch=master)](https://travis-ci.com/billyromano/livedown2)
[![Downloads](https://img.shields.io/npm/dt/livedown2.svg)](https://npmjs.org/package/livedown2)

## Installation

    $ npm install -g livedown2

## Usage

    $ livedown2 --help

## Features

### Plugins

* Emojis :sparkles: :smile: :tada:
* GitHub flavored clickable headings/permalinks
* GitHub flavored checkboxes
* Real-time instant preview
* And more!
* **NEW as of 7/1/2020:** 
    * [Subscript](https://github.com/markdown-it/markdown-it-sub)
    * [Superscript](https://github.com/markdown-it/markdown-it-sup)
    * [Footnote](https://github.com/markdown-it/markdown-it-footnote)
    * [Definition List](https://github.com/markdown-it/markdown-it-deflist)
    * [Abbreviation](https://github.com/markdown-it/markdown-it-abbr)
    * [Insert](https://github.com/markdown-it/markdown-it-ins)
    * [Mark](https://github.com/markdown-it/markdown-it-mark)

### IDE Integrations
This package offers additional integrations for your favorite editors. Make sure to install the `livedown2` package first, then follow the install instructions for each editor plugin.
    
* [Vim plugin](https://github.com/shime/vim-livedown)
* [Emacs plugin](https://github.com/shime/emacs-livedown)
* [Sublime plugin](https://github.com/shime/sublime-livedown)
* [Kakoune plugin](https://github.com/Delapouite/kakoune-livedown)

## Alternatives

* [vim-instant-markdown](https://github.com/suan/vim-instant-markdown)
* [octodown](https://github.com/ianks/octodown)
* [vmd](https://github.com/yoshuawuyts/vmd)
* [markdown-preview](https://github.com/yuanchuan/markdown-preview)
* [grip](https://github.com/joeyespo/grip)
* [gfms](https://github.com/youurayy/gfms)

## License

[MIT](https://tlo.mit.edu/learn-about-intellectual-property/software-and-open-source-licensing)
