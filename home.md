---
title: Well hello there
layout: default
---

#Lines and Dots

<ul>
  {% for post in site.posts limit: 8 %}
    <li><div class="conatiner">{{ post.content | truncatewords: 35}} </div><a href="{{ post.url }}">Read More</a></li>
  {% endfor %}
</ul>
