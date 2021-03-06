[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

## About

This theme is a port of the
[Pop Syntax Theme](https://github.com/luka-lazov/pop-syntax) for the
Atom editor by Luka Lazov, which is meant to pair with the PoP GTK+
theme from System76's [Pop!_OS](https://system76.com/pop). 

The initial cut was done with Martin Haesler's
[ThemeCreator](https://github.com/mswift42/themecreator), and modified
from there.

This requires the themeing support in Emacs 24 and later, so far I've
tested it only against Emacs 25.2.2 in Ubuntu 17.10.

## Installation

### Manual

Download `pop-theme.el` to the directory `~/.emacs.d/themes/`. Add this to your
`.emacs`:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with the interactive function `load-theme` like this:

`M-x load-theme RET pop`

## TODO

* Add missing faces for popular languages to have parity with Zenburn's coverage

