---
layout: page
title: infiniteregress
tagline: back from the past
---
{% include JB/setup %}

{{ post.last }}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




