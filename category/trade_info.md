---
layout: default
title: the trade information category 
---

{% for post in site.posts %}
  {% if post.categories contains "trade_info" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
