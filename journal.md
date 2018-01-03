---
layout: default
title: Journal
categories:
---
<a href='https://github.com/dhakkada/dhakkada.github.io/new/master/_posts'>New post</a>
<a href='https://github.com/dhakkada/dhakkada.github.io/tree/master/_posts/'>Posts</a>
<p/>
### My Journal

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

