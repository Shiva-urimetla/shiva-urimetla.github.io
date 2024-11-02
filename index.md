---
layout: default
title: Home
---

# Welcome to My Blog

Hi, I'm Shiva Urimetla, a tech enthusiast with a passion for cloud, SQL, and cybersecurity.

## Latest Posts
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
