---
layout: default
permalink: /Honorblog/:year/:month/:day/:title:output_ext
title: "Welcome to Honor's Blog!"
---

# Honor's Blog

  {% for post in site.posts %}
  <a href="{{ post.url }}">
    <h2>{{ post.title }}</h2>
    <p>{{ post.date | date_to_string }}</p>
  </a>
{% endfor %}
