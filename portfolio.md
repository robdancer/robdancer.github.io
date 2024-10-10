---
layout: default
title: Portfolio
permalink: /portfolio/
---

A selection of my previous work

<ul>
  {% for post in site.categories["portfolio"][1] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>