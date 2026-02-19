---
layout: default
title: Home
---

# Welcome 👋

This is my Jekyll site hosted on GitHub Pages.

Check out my latest blog posts below:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
