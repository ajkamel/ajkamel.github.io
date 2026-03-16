---
layout: page
title: Writing
---

{% for post in site.posts %}
<div class="post-summary">
  <h3>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </h3>
  <span class="post-date">{{ post.date | date_to_string }}</span>
</div>
{% endfor %}
