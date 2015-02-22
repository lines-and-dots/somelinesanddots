---
title: Welcome to the Studio
layout: defaultstudio
---

#Studio Events
<div class="conatiner">
	<div class="row-fluid">
<ul>
  {% for post in site.posts limit: 8 %}
 {{ post.content | truncatewords: 50}} <a href="{{ post.url }}">Read More</a>
  {% endfor %}
</ul>
</div>