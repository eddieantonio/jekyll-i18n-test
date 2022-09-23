---
title: Home
description: This is the home page.
permalink: /
lang: en
---

Hello!

<section>
<h2>News</h2>
{% for post in site.posts %}
<article>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <blockquote>
    {{ post.excerpt }}
  </blockquote>
  <p><a href="{{ post.url }}">Read more…</a></p>
</article>
{% endfor %}
</section>
