---
layout: page
title: Book reviews
permalink: /book-reviews
---

Here I try to summarise few of the books I have read or am currently reading. You can try to get a soft copy of the books at [Libgen](http://libgen.io).

**List of few of the books I have read and their summary (hopefully !).**


{% for item in site.books-read %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}


**List of few of the books I am currently reading.**


{% for item in site.books-reading %}
  <p><a href="{{ item.url }}">{{ item.title }}</a> {{item.description }} </p>
{% endfor %}