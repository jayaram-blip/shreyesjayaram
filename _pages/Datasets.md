---
layout: page
title: Datasets
permalink: /Datasets/
description: A growing collection of your cool projects.
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---

## Communal Violence Dataset

The Communal Violence Dataset (CVD) is the first systematically collected, geocoded event dataset of Hindu–Muslim communal violence in India covering 2017–2024. The dataset was constructed from the complete Times of India digital archives using a multi-stage computational pipeline combining active learning, transformer-based document classification, large language models, and automated geocoding. Beginning with more than 900,000 newspaper articles, a high-recall BERT classifier trained through active learning identifies potentially relevant reports, which are then processed by large language models to extract structured information on incidents, actors, casualties, event types, dates, and locations. Each incident is subsequently geocoded using the Google Maps API and linked to India's administrative and electoral geography, including Assembly Constituencies. Every observation retains a direct link to its original newspaper article, allowing users to inspect the source material underlying each coded event.

## Interactive Map

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.4/dist/leaflet.min.css" integrity="sha256-q9ba7o845pMPFU+zcAll8rv+gC+fSovKsOoNQ6cynuQ=" crossorigin="" />
<style>
  #cvd-map { width: 100%; height: 640px; border: 1px solid var(--global-divider-color); border-radius: 6px; }
</style>

<div id="cvd-map"></div>

<script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-MgH13bFTTNqsnuEoqNPBLDaqxjGH+lCpqrukmXc8Ppg=" crossorigin=""></script>
<script>
  // Your Leaflet map goes here — container id is "cvd-map" above.
</script>
