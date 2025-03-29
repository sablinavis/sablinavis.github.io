---
title: ""
layout: single
excerpt: "EDA on the Covid19 data from WHO for the period of January 2020 - July 2020."
classes: title-jupyter-notebooks
sidebar:
  disable: true
header:
  teaser: "https://upload.wikimedia.org/wikipedia/commons/3/3b/COVID-19_Outbreak_World_Map_per_Capita.svg"
  caption: "Image from Wikimedia Commons"
classes: wide
---


<div class="inline-image-wrapper">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/COVID-19_Outbreak_World_Map_per_Capita.svg" alt="Covid19" class="inline-image-clickable">
  <a href="https://commons.wikimedia.org/wiki/File:COVID-19_Outbreak_World_Map_per_Capita.svg" target="_blank" rel="noopener noreferrer" class="image-overlay-link">
    source: From Wikimedia
  </a>
</div>


<div>
   <h2 class="title-jupyter-notebooks">Global Covid 19 cases 2020 January - July</h2>
</div>

<div class="gist-container">
  <script src="https://gist.github.com/sablinavis/b44a1623f9b3da57f7988b71993019c7.js"></script>
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
