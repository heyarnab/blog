---
layout: default
title: My Blog
---

<h1>Posts</h1>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
