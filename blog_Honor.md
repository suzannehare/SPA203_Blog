---
layout: default
permalink: pretty
title: "Welcome to Honor's Blog!"
---

# Honor's Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
