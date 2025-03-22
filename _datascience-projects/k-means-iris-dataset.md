---
title: ""
layout: single
excerpt: "K-means with Iris dataset."
classes: title-jupyter-notebooks
sidebar:
  disable: true
header:
  teaser: "https://upload.wikimedia.org/wikipedia/commons/a/a7/Irissetosa1.jpg"
  caption: "Image from Wikimedia Commons"
classes: wide
---

<!-- <div class="inline-image-wrapper">
  <a href="https://commons.wikimedia.org/wiki/File:Irissetosa1.jpg" target="_blank" rel="noopener noreferrer">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Irissetosa1.jpg" alt="Iris Setosa Flower" class="inline-image-clickable">
  </a>
  <div class="image-caption-overlay">Image from Wikimedia Commons</div>
</div> -->


<div class="inline-image-wrapper">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Irissetosa1.jpg" alt="Iris Setosa Flower" class="inline-image-clickable">
  <a href="https://commons.wikimedia.org/wiki/File:Irissetosa1.jpg" target="_blank" rel="noopener noreferrer" class="image-overlay-link">
    source: From Wikimedia
  </a>
</div>


<div>
   <h2 class="title-jupyter-notebooks">K-means with Iris dataset</h2>
</div>

<div class="gist-container">
  <script src="https://gist.github.com/sablinavis/3fe5c4a7b585a51ce7eeb15ea06d7a99.js"></script>
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
