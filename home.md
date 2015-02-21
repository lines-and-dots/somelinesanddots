---
title: Well hello there
layout: default
---

#Lines and Dots
<div class="conatiner">
<ul>
  {% for post in site.posts limit: 8 %}
    <li class="conatiner" class="row-fluid">{{ post.content | truncatewords: 35}} <a href="{{ post.url }}">Read More</a></li>
  {% endfor %}
</ul>
</div>