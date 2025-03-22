---
title: ""
layout: single
excerpt: "Google trends analysis if similar shows tend to be 'popular' because of eachother."
classes: title-jupyter-notebooks
sidebar:
  disable: true
header:
  teaser: "https://upload.wikimedia.org/wikipedia/commons/8/8c/Google_Trends_Logo.png"
  caption: "Image from Wikimedia Commons"
classes: wide
---


<div class="inline-image-wrapper">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Google_Trends_Logo.png" alt="Google Trends" class="inline-image-clickable">
  <a href="https://it.wikipedia.org/wiki/File:Google_Trends_Logo.png" target="_blank" rel="noopener noreferrer" class="image-overlay-link">
    source: From Wikimedia
  </a>
</div>


<div>
   <h2 class="title-jupyter-notebooks">Google trends binged shows</h2>
</div>

<div class="gist-container">
  <script src="https://gist.github.com/sablinavis/f45e33cf499ed787642c1f61548ffd40.js"></script>
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
