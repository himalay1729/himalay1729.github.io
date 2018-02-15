---
layout: page
title: Things I am learning
permalink: /learning-topics
---

Hello, here I post about things I am currently learning.

{% for item in site.learning-topics %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}