# vim-jsx-improve
[![](http://img.shields.io/github/issues/neoclide/vim-jsx-improve.svg)](https://github.com/neoclide/vim-jsx-improve/issues)
[![](http://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Makes your javascript files support React jsx correctly.

Javascript syntax from [pangloss/vim-javascript](https://github.com/pangloss/vim-javascript)

Jsx highlight and indent code changed from [MaxMEllon/vim-jsx-pretty](https://github.com/MaxMEllon/vim-jsx-pretty)

* Fixed syntax highlighting and indentation for React jsx files.
* Works well with xml.vim

This plugin have no dependency, all the code you need for jsx and javascript is
included.

**Note:** you need to disable **vim-javascript** plugin if have installed, I have to
change some highlight group to make it works with jsx.

### Installation

Use pathogen or vundle is recommended. Vundle:

    Plugin 'chemzqm/vim-jsx-improve'

### Quick jump to function braces

You can use `[[` `]]` `[]` `][` to quick jump to `{` `}` position of functions, set `g:jsx_improve_motion_disable` to `1` to disable it.

### GIF

![2016-12-10 01_27_59](https://cloud.githubusercontent.com/assets/251450/21058283/26d3b946-be78-11e6-8b1e-78e146ec3496.gif)

The colorscheme is [gruvbox](https://github.com/morhetz/gruvbox)

The keystroke visualizer is [keycastr](https://github.com/sdeken/keycastr)

### Feed back welcome

Feel free to open a ticket if your have problem with this plugin.
