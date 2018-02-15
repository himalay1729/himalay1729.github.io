---
layout: page
title: Book reviews
permalink: /book-reviews
---

Here I review few of the books I have read or am currently reading.

{% for item in site.book-reviews %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}