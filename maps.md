---
layout: default
title: Maps
nav_order: 4
---

# Maps

A collection of geographic visualizations and cartographic work.

{% for map in site.maps %}

## [{{ map.title }}]({{ map.url }})

[![{{ map.title }}]({{ map.image }})]({{ map.image }})

{{ map.content | strip_html | truncatewords: 30 }}

---

{% endfor %}
