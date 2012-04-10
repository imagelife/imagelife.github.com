---
layout: page
title: imagelife's blog !
tagline: Supporting tagline
---
{% include JB/setup %}

记录
随意


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

