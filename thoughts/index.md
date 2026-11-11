---
layout: default
title: Thoughts & Reflections
---

# Thoughts & Reflections

I like to explore thoughts and analogies on various different aspects. Sharing them here for fun — something to wonder about and not take too seriously.

## Recent thoughts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) <span class="post-list-date">{{ post.date | date: "%-d %b %Y" }}</span>{% assign summary = post.summary | default: post.description %}{% if summary %} — {{ summary }}{% endif %}
{% endfor %}
