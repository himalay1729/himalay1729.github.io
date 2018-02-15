---
layout: page
title: Research interests
permalink: /research-interest
---

Here I write about things that I have worked on or have an interest in.

{% for item in site.research-interests %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}