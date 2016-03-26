---
layout: archive
title: "Painting Collections"
date: 2016-03-25
modified:
excerpt: # "Painting Collections."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.collections %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
