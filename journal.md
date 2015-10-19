---
layout: default
title: Journal
categories:
---
<a href='http://tinypress.co'>x</a>
<a href='https://github.com/dhakkada/dhakkada.github.io/tree/master/_posts/'>.</a>
<p/>
### My Journal

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

