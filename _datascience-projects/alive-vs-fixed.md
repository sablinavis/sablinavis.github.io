---
title: ""
layout: single
excerpt: "Analysis of protein expression between alive and fixed sfpH pHluorin E.coli cells."
classes: title-jupyter-notebooks
sidebar:
  disable: true
header:
  teaser: "https://upload.wikimedia.org/wikipedia/commons/2/20/PDB_1ema_EBI.jpg"
  caption: "Image from Wikimedia Commons"
classes: wide
---


<div class="inline-image-wrapper">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/PDB_1ema_EBI.jpg" alt="Phluorin" class="inline-image-clickable">
  <a href="https://commons.wikimedia.org/wiki/File:PDB_1ema_EBI.jpg" target="_blank" rel="noopener noreferrer" class="image-overlay-link">
    source: From Wikimedia
  </a>
</div>


<div>
   <h2 class="title-jupyter-notebooks">Alive and fixed sfpH pHluorin E.coli cells</h2>
</div>

<div class="gist-container">
  <script src="https://gist.github.com/sablinavis/3549e07e25480927f38aaddb431ef1da.js"></script>
</div>

<div>
   <h2 class="title-jupyter-notebooks">ZapA expression in E.coli cells</h2>
</div>
<div class="gist-container">
  <script src="https://gist.github.com/sablinavis/0f281f01e21c06962e280f1220fe1790.js"></script>
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
