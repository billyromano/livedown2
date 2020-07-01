# Livedown2
[![Build Status](https://travis-ci.com/billyromano/livedown2.svg?branch=master)](https://travis-ci.com/billyromano/livedown2)
[![Downloads](https://img.shields.io/npm/dt/livedown2.svg)](https://npmjs.org/package/livedown2)

*Originally based on [shive/linedown](https://github.com/shime/livedown).*

## Table of Contents
- [Overview](#overview)
    - [Demos.](#demos)
- [Installation](#installation)
- [Usage](#usage)
    - [Examples](#examples)
        - [Help Command](#help-command)
        - [Specify port](#specify-port)
        - [Open README.md preview in browser](#open-readme.md-preview-in-browser)
        - [Open README.md preview in a specific browser with arguments](#open-readme.md-preview-in-a-specific-browser-with-arguments)
- [Features](#features)
    - [Plugins](#plugins)
    - [IDE Integrations](#ide-integrations)
- [Alternatives](#alternatives)
- [License](#license)

## Overview

Easily render markdown documents using the command line (CLI) based on the next generation markdown parser in javascript, with pluggable syntax [Markdown it!](https://github.com/markdown-it)

* Follows the [CommonMark spec](http://spec.commonmark.org/) + adds syntax extensions & sugar (URL autolinking, typographer).
* Configurable syntax! You can add new rules and even replace existing ones.
* High speed.
* [Safe](https://github.com/markdown-it/markdown-it/tree/master/docs/security.md) by default.
* Community-written plugins and other packages on npm.

### Demos
View the [Live Demo](https://markdown-it.github.io) to try it out or check out the screen capture below.
![](https://twobucks.co/assets/livedown.gif)

## Installation

    $ npm i -g livedown2

## Usage

Typing either `livedown` or `livedown2` will work.

    $ livedown

### Examples
#### Help
    $ livedown -h

#### Specify port
    $ livedown start README.md --port 4242

#### Open README.md preview in browser
    $ livedown start README.md --open

#### Open README.md preview in a specific browser with arguments
This feature relies on specific CLI commands available for the browser of your choosing, e.g., --incognito for Google Chrome.

    $ livedown start README.md --open --browser "'google chrome' --incognito"
    
## Features

### Installed Plugins

* [Emoji](https://github.com/markdown-it/markdown-it-emoji) :sparkles: :smile: :tada:
* [GitHub flavored clickable headings/permalinks](https://github.com/Flet/markdown-it-github-headings)
* [GitHub flavored checkboxes](https://github.com/linsir/markdown-it-task-checkbox)
* Real-time instant preview
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
