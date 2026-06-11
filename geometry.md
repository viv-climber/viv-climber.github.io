---
layout: page
title: Geometry
permalink: /geometry/
---

{% for post in site.posts %}
  {% if post.category == "geometry" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
