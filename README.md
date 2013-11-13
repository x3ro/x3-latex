# Whats this?

These are some LaTeX templates I made mainly for myself, because I was tired of 
gathering everything over and over again. If you have suggestion or something missing
somewhere, feel free to write a bug report :)


# How to use?

Clone this repo into a directory where LaTeX will find it. For me, on Mac OS X using MacTeX
that is `~/Library/texmf/tex/latex/`, but that might differ for you.

Thats it. You can use the `x3-init` script to automatically setup "project" structure for you,
but you'll also need to get [`omgtex.rb`](https://github.com/x3ro/dotfiles/blob/master/.bin/omgtex.rb),
which is a script I use for "building" TeX files.


## Using BibTex

The `omgtex.rb` command has support for bibtex (-b option), and so do the templates. The BibTeX configuration is done in `x3-general-bibtex`. Currently, the ["x3-dcu"](https://github.com/x3ro/custom-dcu.bst) bibliography style (which I had to adapt from dcu.bst) is hard-coded there. If this is bothering you, please create an issue and I'll fix it. Since I'm currently assuming to be the only person using these templates, it is not a priority until then :)


# FAQ

Nobody has asked me any questions about my templates so far ;) If you want to use them, and can't get
them to work, you can create an issue or drop me a message on [Twitter](http://twitter.com/x3rames).


# License

These templates are licensed under the MIT License, see the `LICENSE` file for more information.
