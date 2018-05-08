---
layout: page
title: Things I am learning
permalink: /learning-topics
---

Here I write about things I am currently learning. This looks to be a fun way to retain what I learn and also to understand things better.

{% for item in site.learning-topics %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}