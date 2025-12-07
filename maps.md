---
layout: default
title: Maps
nav_order: 4
---

# Maps

A collection of geographic visualizations and cartographic work.

{% for post in site.categories.maps %}

## [{{ post.title }}]({{ post.url }})

[![{{ post.title }}]({{ post.image }})]({{ post.image }})

{{ post.content | strip_html | truncatewords: 30 }}

---

{% endfor %}
