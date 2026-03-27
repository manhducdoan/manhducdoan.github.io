---
layout: default
title: Blog
permalink: /blog/
---

## Blog

Occasional notes on economics, research methods, and academic life.

---

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date: "%-d %B %Y" }}</span>
  </li>
{% endfor %}
{% if site.posts.size == 0 %}
  <li>No posts yet. Check back soon.</li>
{% endif %}
</ul>
