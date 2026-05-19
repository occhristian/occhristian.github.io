---
layout: page
title: Writing
description: Tutorials, dev notes, debugging stories, and practical technical guides.
permalink: /blog/
---

<div class="post-list">
{% for post in site.posts %}
<article class="post-card wide">
  <p>{{ post.date | date: "%B %-d, %Y" }}</p>
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <span>{{ post.categories | join: ', ' }}</span>
</article>
{% endfor %}
</div>
