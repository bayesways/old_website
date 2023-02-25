---
layout: page
title: /math-club
permalink: /math-club/
---

Home to the world famous math club, a book club for math books.

__Now in session!!__

<details><summary>See here all relevant posts</summary>
<ul>
  {% for post in site.categories.math-club %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
