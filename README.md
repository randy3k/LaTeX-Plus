LaTeXBox
=====

-------
**Important:** I guess LaTeXBox has finished its historical goal after the
LaTeX syntax has [merged](https://github.com/sublimehq/Packages/pull/370) into
Sublime Text. Additionally, the rapid recent development of
[LaTeXTools](https://github.com/SublimeText/LaTeXTools) shames the lake of
functionalities of LaTeXBox. Sorry guys, I am giving up LaTeXBox and switch
to LaTeXTools (and you should too).

For those who loves the keybinds shipped by LaTeXBox, I have moved the keybinds to a new package [LaTeXZeta](https://github.com/randy3k/LaTeXZeta) which is compartiable with LaTeXTools.

If you have a strong interest to be a maintainer of LaTeXBox, please let me know.

-------

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&amp;business=Randy%2ecs%2elai%40gmail%2ecom&amp;lc=US&amp;item_name=Package&amp;currency_code=USD&amp;bn=PP%2dDonationsBF%3apaypal%2ddonate%2dyellow%2esvg%3aNonHosted" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-blue.svg" /></a>
<a href="https://gratipay.com/~randy3k/" title="Donate to this project using Gratipay"><img src="https://img.shields.io/badge/gratipay-donate-yellow.svg" /></a>


LaTeXBox is a multi-platform LaTeX package for [Sublime Text 3](https://www.sublimetext.com/3). 
It works on OSX, Windows and Linux. LaTeXBox aims to be lightweight, extensible but self contained. If
you are looking for a full feature package, see, for example
[LaTeXing](http://latexing.com) or
[LaTeXTools](https://github.com/SublimeText/LaTeXTools). A lot of ideas are
actually inspired by these two packages. So why this package? If you love
customization or want to be able to hack somethings, this package would be
your choice as LaTeXing is not open source and LaTeXTools is too bulky.


### Features
* OSX, Windows and Linux support
* Automatic process of generating a LaTeX document by using `latexmk`
* AutoCompletion for `\ref`, `\cite`, `\include`, `\input`, `\includegrpahics` etc...
* Keybinds for mathematics symbols, e.g. `` `a `` types `\alpha`.
* Backward and forward sync of various PDF viewers
* Automatch for `()`, `[]`, `{}`, `\(\)`, `\(\)`, `\{\}`, `\left` - `\right` pairs, `$$` and quotation marks.
* More…

### Wiki

- [Installation](https://github.com/randy3k/LaTeXBox/wiki/Installation)
- [User Manual](https://github.com/randy3k/LaTeXBox/wiki/User Manual)
- [Project Setup](https://github.com/randy3k/LaTeXBox/wiki/Project-Setup)
- [LaTeXBox Options](https://github.com/randy3k/LaTeXBox/wiki/Options)
- [BracketHighlighter Settings](https://github.com/randy3k/LaTeXBox/wiki/BracketHighlighter-settings)

### Sublime Text 2 compatibility

While it is possible to backward port to ST2,  I would rather keep it ST3 only for easier maintenance.

### License

```text
    LaTeXBox Package for Sublime Text
    Copyright (C) 2016 Randy Lai

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
```
