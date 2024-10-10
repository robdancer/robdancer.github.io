---
layout: default
title: Portfolio
permalink: /portfolio/
---

A selection of my previous work

{% for post in site.categories.portfolio %}
  <div class="portfolio-entry">
  <a href="{{ post.url }}">{{ post.title }}</a>
  </div>
{% endfor %}