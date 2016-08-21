# reveal-jekyll-slideserver
A Jekyll-based static fileserver for Github-hosted Reveal.js slidedecks

Jekyll-Reveal.js integration based on documentation from @jpmoral's [blog post](http://jpmoral.com/blogging/2015/07/29/hosting-revealjs-slides-on-jekyll.html) building on @luugiathuy's [presentation](http://luugiathuy.com/slides/jekyll-create-slides-with-revealjs/#/).

Sample slidedeck created mostly for testing purposes:  (https://mjvo.github.io/reveal-jekyll-slideserver/sample.html) <a href='_slidedecks/sample.md'>Slide Source</a>

Slidedecks use standard

## Libraries used:

This project integrates the Reveal.js core with several plugins.
* [Reveal.js](https://github.com/hakimel/reveal.js) (v3.3.0)
* [Menu](https://github.com/denehyg/reveal.js-menu) (plugin)
* [Chalkboard](https://github.com/rajgoel/reveal.js-plugins/tree/master/chalkboard) (plugin)
* [Reveal Code Focus](https://github.com/demoneaux/reveal-code-focus) (plugin)


## Notes:

* Slides (.md or .html) must be placed in `_slidedecks` directory.  Subfolders may be used for organization.
* Fix added to Reveal.js 3.3.0:  css updated to [address fullscreen issue](https://github.com/hakimel/reveal.js/commit/a12a17b2d7053fad006ae9914309e8fb56c44329)
* Chalkboard:  Default keybindings changed for the Chalkboard plugin to avoid conflicts.

## to do

* [] Add Jekyll page for rolling list of slidedecks?
* [] Add / reference installation instructions
* [] Add / reference usage instructions
* [] Add chalkboard pen color picker to custom menu in Menu plugin.
* [] Add highlight.js theme picker to custom menu in Menu plugin.
