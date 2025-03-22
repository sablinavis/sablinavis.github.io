---
title: "Projects"
layout: splash
permalink: /projects/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/projectsintro.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Projects: apps, Datastories, Datascience proejcts and Dashboards."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/datastories-logo.png
    title: "LOD Datastories"
    excerpt: "Datastories built with SPARQL queries in Triply environment"
  - image_path: /assets/images/leafletLOD-logo.png
    alt: "placeholder image 1"
    title: "Leaflet LOD app"
    excerpt: "A demonstrative leaflet app that uses a SPARQL-query RestAPI to populate the map."
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
  - image_path: /assets/images/handleiding-logo.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "RCE PoolParty handleiding"
    excerpt: "Specifieke PoolParty handleiding voor de RCE."
    url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

---
