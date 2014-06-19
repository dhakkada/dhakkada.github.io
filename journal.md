---
layout: post
title: Journal
cover: null.jpg
date:   2013-12-09 12:00:00
categories: posts
---

#### Updates<a href='https://github.com/dhakkada/dhakkada.github.io/tree/master/_posts/mylens'>.</a>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

