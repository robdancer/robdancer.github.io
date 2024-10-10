---
layout: default
title: Portfolio
permalink: /portfolio/
---

A selection of my previous work t6

<ul>
  {% for post in site.categories["portfolio"][1] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

Test

{% for tag in site.categories %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}