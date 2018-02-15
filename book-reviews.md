---
layout: page
title: Book reviews
permalink: /book-reviews
---

Hello, here I review few of the books I have read or wish to read.

{% for item in site.book-reviews %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}