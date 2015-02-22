---
title: Well hello there
layout: default
---

#Lines and Dots
<div class="conatiner">
	<div class="row-fluid">
<ul>
  {% for post in site.posts limit: 8 %}
    {{ post.content | truncatewords: 35}} <a href="{{ post.url }}">Read More</a>
  {% endfor %}
</ul>
</div>
</div>