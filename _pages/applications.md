---
title: "Open Source Applications and Websites"
layout: splash
permalink: /applications/
author_profile: False
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner-applications.png
  actions:
    - label: "Github"
      url: "https://github.com/sablinavis"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: ""
intro: 
  - excerpt: 'Here you can find a summary of the projects I have worked on or am curretly working on that are public for viewing.'
feature_row:
  - image_path: /assets/images/amsterdam-leaflet.png
    title: "Straatvernoemer - Amsterdam"
    excerpt: "Naar wie is de straat vernoemd?."
    url: "https://github.com/sablinavis/leaflet-sparql-amsterdam"
    btn_label: "View App"
    btn_class: "btn--custom"
  - image_path: /assets/images/leafletLOD-logo.png
    alt: "placeholder image 1"
    title: "Test Leaflet-Python with SPARQL endpoint."
    excerpt: "A demonstrative leaflet app that uses a SPARQL-query RestAPI to populate the map."
    url: "https://sablinavis.github.io/Leaflet-LOD/"
    btn_label: "View App"
    btn_class: "btn--custom"
  - image_path: /assets/images/amsterdam-leaflet.png
    title: "Wikipedia to N-triples"
    excerpt: "Crawling wikipedia and transforming title and description to linked data."
    url: /applications/wikipedia-to-nt/
    btn_label: "View App"
    btn_class: "btn--custom"
  - image_path: /assets/images/handleiding-logo.png
    alt: "placeholder image 2"
    title: "RCE PoolParty handleiding"
    excerpt: "Specifieke PoolParty handleiding voor de RCE."
    url: "https://cultureelerfgoed.github.io/Poolparty-User-Documentation/"
    btn_label: "View Site"
    btn_class: "btn--custom"
  # - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
  #   title: "Placeholder 3"
  #   excerpt: "This is some sample content that goes here with **Markdown** formatting."
# feature_row2:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

---
