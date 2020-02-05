---
layout: default
title:  "Welcome to Honor's Blog!"
permalink: /Honorblog/:year/:month/:day/:title:output_ext
---
Here you go


<ul>
  {% for post in site.posts %}
  <a href="{{ post.url }}">
    <h2>{{ post.title }}</h2>
    <p>{{ post.date | date_to_string }}</p>
  </a>
{% endfor %}
</ul>
