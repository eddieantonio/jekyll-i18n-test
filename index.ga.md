---
title: Leathanach baile
description: "Ní féidir liom Gaeilge a labhairt. :("
permalink: /
lang: ga
---

Dia duit!

<h2>Nuacht</h2>
{% for post in site.posts %}
<article>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <blockquote>
    {{ post.excerpt }}
  </blockquote>
  <p><a href="{{ post.url }}">Leigh Nios mo…</a></p>
</article>
{% endfor %}
