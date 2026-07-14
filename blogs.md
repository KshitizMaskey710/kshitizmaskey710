---
layout: page
title: Blogs & Case Studies
eyebrow: Writing
description: Reflections on Agile, team leadership, personal clarity, delivery systems, and practical enablement.
permalink: /blogs/
nav: Blogs
wide: true
---

<div class="card-grid blog-grid">
{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts %}
<article class="card"><p class="eyebrow">{{ post.category_label }}</p><h2>{{ post.title }}</h2><span class="rule"></span><p>{{ post.description }}</p><a class="text-link" href="{{ post.url | relative_url }}">Read {{ post.category_label | downcase }} →</a></article>
{% endfor %}
</div>
