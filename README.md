SassDoc theme boilerplate
=========================

So you want to build your own theme? You've come to the appropriate place.
This is a blank theme so you can build yours based on this one, without
too much hassle hopefully.

This theme has no CSS, no JavaScript and barely displays any information
at all. All it has is a working view that explains how you should
proceed to output content about your documented items. For more
informations about what's being passed to the view, be sure to read
[this entry](https://github.com/SassDoc/sassdoc/wiki/SassDoc-Data-Interface)
from SassDoc's wiki.

Note that this theme uses:

* [Themeleon](https://github.com/themeleon/themeleon) as a theming
  engine (but you could do without),
* [Swig](http://paularmstrong.github.io/swig/) as a template engine,
  through
  [`themeleon-swig`](https://github.com/themeleon/themeleon-swig) (but
  you could do without).

For extra informations about building your own theme, be sure to have a
look at [the related page](https://github.com/SassDoc/sassdoc/wiki/Using-Your-Own-Theme) in
SassDoc's wiki.

**Don't forget to `npm install` in the theme directory if you require
it with the `--theme` option. Otherwise, this is done automatically when
you require a theme via `npm`.**

> *TIP: You might want to also have a look at the SassDoc [theme generator](https://github.com/SassDoc/generator-sassdoc-theme).  
It will customize and output all the boilerplate files for you.*
