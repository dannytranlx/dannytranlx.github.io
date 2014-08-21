---
layout: default
title: Blog · Danny Tran
background: default.jpg
---

##Blog
<hr>
<ul class="listing">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date: "%B %-d, %Y" | upcase }}</span>
    <a href='{{ post.url }}'>{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
