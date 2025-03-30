---
title: "Wikipedia to N-triples"
layout: single
excerpt: "Wikipedia Artists to Linked Open Data in N-triples."
classes: title-jupyter-notebooks
permalink: /applications/wikipedia-to-nt/
author_profile: False
sidebar:
  disable: true
header:
  teaser: ""
  caption: "Image from Wikimedia Commons"
classes: wide
---


<div class="inline-image-wrapper">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/Screenshot_from_2021-05-17_12-26-27.png" alt="Wikipedia-to-LOD" class="inline-image-clickable">
  <a href="https://commons.wikimedia.org/wiki/File:Screenshot_from_2021-05-17_12-26-27.png" target="_blank" rel="noopener noreferrer" class="image-overlay-link">
    source: From Wikimedia
  </a>
</div>


<div>
   <h2 class="title-jupyter-notebooks">Script to match a list to Wikipedia artikle titles, extract description, and transform to LOD</h2>
</div>

<div class="gist-container">
  <script src="https://gist.github.com/sablinavis/30ea5a4236e119493f48dfc3b6d7d0df.js"></script>
</div>

<script>
  window.addEventListener('load', function () {
    // Wait a moment for the iframe to load
    setTimeout(() => {
      const gistIframe = document.querySelector('.gist-container iframe');
      if (gistIframe) {
        // Try to set a bigger height manually
        gistIframe.style.height = '1000px'; // or whatever value works best
      }
    }, 1000); // delay to allow iframe to load
  });
</script>
