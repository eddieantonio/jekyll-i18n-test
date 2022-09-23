---
title: Leathanach baile
permalink: /
lang: ga
---

Dia duit!

# Nuacht

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})
{% endfor %}
