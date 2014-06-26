---
layout: posts
title: Journal
categories:
---
### My Journal <a href='https://github.com/dhakkada/dhakkada.github.io/tree/master/_posts/mylens'>.</a>


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

