---
layout: default
title: This is Raiffa's blog
permalink: pretty
---

Blog

{% for post in site.posts %}
{{ post.title }}
{% endfor %}

here

{% for post in site.posts %}
{{ post.title }} {{ post.excerpt }}
{% endfor %}
