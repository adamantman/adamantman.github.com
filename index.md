---
layout: page
title: I like to use the word *damn* very much.
tagline: Any questions?
---
{% include JB/setup %}

## All posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


