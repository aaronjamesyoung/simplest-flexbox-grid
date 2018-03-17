# The Simplest Flexbox grid ever!

This is a set of simple CSS preprocessor mixins meant to provide a basic grid for your websites.
<https://ajy.co/the-simplest-sass-flexbox-grid-ever>

See a demo and play with it:

* [Sass Demo (Codepen)](http://codepen.io/aaronjamesyoung/pen/yezKpj)
* [Stylus Demo (Codepen)](https://codepen.io/narkoleptika/pen/eMJyjW)

## The basics

This repo provides a mixin called `_fg()`. You can use this mixin on a grid *container*. It will distribute the child elements of that container into a grid layout as specified in the mixin.

The mixin accepts three arguments:

1. Number of columns OR layout
2. Width of gutter between grid columns
3. Amount of padding in grid columns

You are able to do some interesting stuff, e.g.:

* Set an arbitrary number of columns in your container. The columns will be of equal width by default.
* Set a custom layout (e.g., three columns of 1x, 3x, and 2x width) in your container
* Override width (or other properties) of a particular column as needed
* Columns will wrap in a container. For example, if you specify a three column layout but provide six columns in the markup, you'll get a second row of columns using the correct layout.

**Choose Sass (scss) or Stylus below to view detailed usage instructions:**

* [Sass](/sass)
* [Stylus](/stylus)

## Getting it

After cloning this repository, you'll find the relevant sass or stylus files in their respective directories.

## Credits

* [Roland Toth](https://github.com/rolandtoth) augmented the original mixin to accept a layout; taught me a couple cool SCSS tricks I wasn't aware of
* [Jayesh Saraf](https://github.com/SarafJayesh) supplied a breakpoint mixin
* [Narkoleptika](https://github.com/Narkoleptika) provided the Stylus port
