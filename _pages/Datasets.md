---
layout: page
title: Datasets
permalink: /datasets/
description:
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---


<style>
  .ucla-heading { color: #2774AE; }
</style>


<h3 class="ucla-heading">Communal Violence Dataset</h3>

## Communal Violence Dataset

The Communal Violence Dataset (CVD) systematically records episodes of Hindu–Muslim communal violence in India between 2017–2024. To construct this dataset, I scraped over 1 million articles from the archives of the Times of India, India's newspaper record. Employing modern computational tools, I systematically identified, extracted, geolocated, and deduplicated reports of communal violence, before spatially joining them to various maps of India's administrative and electoral geographical units. Each record retains a direct link to its original newspaper article, enabling easy inspection of the underlying source material.

<h3 class="ucla-heading">Interactive Map</h3>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.4/dist/leaflet.min.css" integrity="sha256-q9ba7o845pMPFU+zcAll8rv+gC+fSovKsOoNQ6cynuQ=" crossorigin="" />
<style>
  #cvd-map { width: 100%; height: 640px; border: 1px solid var(--global-divider-color); border-radius: 6px; }
</style>

<div id="cvd-map"></div>

<script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-MgH13bFTTNqsnuEoqNPBLDaqxjGH+lCpqrukmXc8Ppg=" crossorigin=""></script>
<script>
  // Your Leaflet map goes here — container id is "cvd-map" above.
</script>
