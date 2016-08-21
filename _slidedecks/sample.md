---
layout: slidedeck
title: My Test Slidedeck
description: A test slidedeck for integration into Jekyll Github Pages
category:  talks
theme: sky
transition: convex
---

<section data-markdown>
## What is this?

This is a barebones implementation of [Jekyll](http://jekyllrb.com/) integrated with [reveal.js](https://github.com/hakimel/reveal.js/) enabling the serving of slidedecks from [Github](https://github.com).

Source and important caveats/notes available [here](https://github.com/mjvo/reveal-jekyll-slideserver)
</section>

<section data-markdown>
    <script type="text/template">
## slide 2
<!--linebreaks by double-space and RETURN -->
> "This is a quote"  
> &#8212; by <cite>someone</cite>
  </script>
</section>

<section>
    <h3>Code</h3>
    <h4>with Fragment Highlighting (HTML)</h4>
    <pre><code data-noescape>
      var x;
      x = x++;
    <mark class="fragment" data-fragment-index="1">  console.log(x);</mark>
    </code></pre>
</section>

<section data-markdown>
    <script type="text/template">

## Markdown Code Test
### with fragments
<pre><code data-noescape>
  var x;
  x = x++;
  <mark class="fragment" data-fragment-index="1">  console.log(x);</mark>
  var y;

</code></pre>

* Item 1 <!-- .element: class="fragment" data-fragment-index="1" -->
  </script>
</section>

<section data-markdown>
    <script type="text/template">

## Title
![arduino](images/arduino.jpg) <!-- .element: style="width:60%" -->

  </script>
</section>

<section data-markdown>
    <script type="text/template">

col1|col2
:---:|:---:
data|data2
data3|data4

  </script>
</section>

<section data-markdown>
    <script type="text/template">

## Fragments
* Item 1 <!-- .element: class="fragment highlight-current-blue" -->
* Item 2 <!-- .element: class="fragment" -->

    </script>
</section>

<section>
<!-- <iframe width="100%" height="500" src="//jsfiddle.net/mjvo/qay021qb/15/embedded/" allowfullscreen="allowfullscreen" frameborder="0"></iframe> -->
<pre class="_cssdeck_embed" data-pane="js" data-height="500" data-user="mjvo" data-href="mjvo-p5js" data-version="0"></pre><script async src="http://cssdeck.com/assets/js/embed.js"></script>

</section>
