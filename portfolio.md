---
layout: default
title: Portfolio
permalink: /portfolio/
---

A selection of my previous work:

{% for post in site.categories.portfolio %}
  <div class="portfolio-entry">
  <a href="{{ post.url }}">{{ post.title }}</a>
    {% for tag in post.tags %}
    <span class='project-tag'> {{ tag }} </span>
  {% endfor %}
  </div>
{% endfor %}