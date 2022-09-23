---
title: Home
permalink: /
lang: en
---

Hello!

# News

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})
{% endfor %}
