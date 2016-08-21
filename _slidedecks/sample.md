---
layout: slidedeck
title: About Reveal-Jekyll-Slideserver
description: A test slidedeck for integration into Jekyll Github Pages
category:  sample
theme: black
transition: convex
---

<section data-markdown>
## What is this?

This is a barebones implementation of [Jekyll](http://jekyllrb.com/), integrated with [reveal.js](https://github.com/hakimel/reveal.js/) to enable the serving of slidedecks from [Github](https://github.com).

It implements the following [reveal.js](https://github.com/hakimel/reveal.js/) plugins:
* [Menu](https://github.com/denehyg/reveal.js-menu)
* [Chalkboard](https://github.com/rajgoel/reveal.js-plugins/tree/master/chalkboard)
* [Reveal Code Focus](https://github.com/demoneaux/reveal-code-focus)

Source and important caveats/notes available [here!](https://github.com/mjvo/reveal-jekyll-slideserver)
</section>

<section data-markdown>
    <script type="text/template">
## Reveal.js
Leverages the power and usability of the [reveal.js](https://github.com/hakimel/reveal.js/) HTML presentation framework:
* HTML and Markdown-based slide creation
* 11 Core Themes (and theme-able!) with 6 slide transitions
* Horizontal and Vertical slide navigation
* Fullscreen presentation mode (Press "f" to toggle)
* and [more](http://lab.hakim.se/reveal-js)...
</script>
</section>

<section>

  <section data-markdown>
    <script type="text/template">
    ## Example Slides
    <br />
    navigate down to view  
    &#x2193;  
    <br />
    or navigate right to skip to information about plugins &#x2192;  
    </script>
  </section>

  <section data-markdown>
    <script type="text/template">
    ### lists
    <br />
    * Unordered
    * Another Item
-----
    1. Ordered
    2. Item 2
    </script>
  </section>

  <section data-markdown>
    <script type="text/template">
    ### images
    ![Arduino](images/arduino.jpg) <!-- .element: style="width:60%" -->
    </script>
  </section>

  <section data-markdown>
      <script type="text/template">
      ### Quotes
      <!--linebreaks by double-space and RETURN -->
      > "This is a quote"  
      > &#8212; by <cite>someone</cite>  

      </script>
  </section>

  <section>
    <h3>Code</h3>
    <pre><code>
      var x;
      x = x++;
      console.log(x);
    </code></pre>
    </section>

    <section data-background="http://i.imgur.com/ggH06.gif" data-background-size="100%">
    <h2>Gif Backgrounds</h2>
    <h3>Wheeee!!!!</h3>
    </section>

</section>

<section>

  <section data-markdown>
    <script type="text/template">
    ## plugins  
    <br />
    navigate down  
    &#x2193;
    </script>
  </section>

  <section data-markdown>
  <script type="text/template">
  ### [Menu](https://github.com/denehyg/reveal.js-menu)
  <br />
  Press "m" or click the <i class="fa fa-bars"></i> button (lower-left) to access  
  <br />
  &#x2713; Slide navigation  
  &#x2713; Dynamic theme switching
  </script>
  </section>  

  <section data-markdown>
  <script type="text/template">
  ### [Chalkboard](https://github.com/rajgoel/reveal.js-plugins/tree/master/chalkboard)
  <br />
  * Annotate current slide while presenting (toggle with "a")
  * Access and a freeform chalkboard (toggle with "c")
  * Also accessible by buttons in the lower left ( <i class="fa fa-pencil-square-o"></i> and <i class="fa fa-pencil"></i> )
  * Press "DEL" to clear
  </script>
  </section>

  <section>
    <h2><a href="https://github.com/demoneaux/reveal-code-focus">Reveal-Code-Focus</a></h2>
    <p><small>Uses <a href="https://highlightjs.org/">highlight.js</a> for code formatting...</small></p>
    <pre><code>
    // Useless comment.
    alert('hi');
    </code></pre>
    <p><small>... and syncs code highlighting with fragment reveals.</small></p>
    <p class="fragment" data-code-focus="2">This focuses on the comment.</p>
    <p class="fragment" data-code-focus="3">This focuses on the alert();</p>
    <p class="fragment"><em>Slideshow continues</em> &#x2192; &#x2192;</p>
  </section>

</section>

<section>
  <p>For more information:<br /><a href="https://github.com/mjvo/reveal-jekyll-slideserver" target="_blank">https://github.com/mjvo/reveal-jekyll-slideserver</a></p>
</section>

<section>
  <h1>Thanks!</h1>
</section>
