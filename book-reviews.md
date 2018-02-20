---
layout: page
title: Book reviews
permalink: /book-reviews
---

Here I try to summarise few of the books I have read or am currently reading. You can try to get a soft copy of the books at [Libgen](http://libgen.io).

{% for item in site.book-reviews %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}