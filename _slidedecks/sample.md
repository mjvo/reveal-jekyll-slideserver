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

Source and important caveats/notes available [here](https://github.com/mjvo/slide-server)
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
    <h3>Code with Fragment Highlighting (HTML)</h3>
    <pre><code data-noescape>
      var x;
      x = x++;
    <mark class="fragment" data-fragment-index="1">  console.log(x);</mark>
    </code></pre>
    <p class="fragment" data-fragment-index="1">Appear at the same time</p>
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
