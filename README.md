# slide-server
A Jekyll-based static fileserver for Github-hosted Reveal.js slidedecks

Jekyll-Reveal.js integration based on documentation from @jpmoral's [blog post](http://jpmoral.com/blogging/2015/07/29/hosting-revealjs-slides-on-jekyll.html) building on @luugiathuy's [presentation](http://luugiathuy.com/slides/jekyll-create-slides-with-revealjs/#/).

Sample slidedeck created mostly for testing purposes:  (http://mjvo.github.io/slide-server/sample.html) [Source](https://github.com/mjvo/slide-server/blob/gh-pages/_slidedecks/sample.md)

Slidedecks use standard

## Libraries used:

This project integrates the Reveal.js core with several plugins.
* [Reveal.js](https://github.com/hakimel/reveal.js) (v3.3.0)
* [Menu](https://github.com/denehyg/reveal.js-menu) (plugin)
* [Chalkboard](https://github.com/rajgoel/reveal.js-plugins/tree/master/chalkboard) (plugin)


## Notes:

* Slides (.md or .html) should be placed in `_slidedecks`.  Subfolders may be used.
* Fix added to Reveal.js 3.3.0:  css updated to [address fullscreen issue](https://github.com/hakimel/reveal.js/commit/a12a17b2d7053fad006ae9914309e8fb56c44329)
* You must access your slides with .html extension addressing (e.g. `example.com/slide.html` and not `example.com/slide/`).  This is necessary for path-relative image URLs to work in slidedecks.
* Chalkboard:  Default keybindings changed for the Chalkboard plugin to avoid conflicts.

## to do

* [] Add Jekyll page for rolling list of slidedecks?
* [] Add / reference installation instructions
* [] Add / reference usage instructions
* [] Add chalkboard pen color picker to custom menu in Menu plugin.
