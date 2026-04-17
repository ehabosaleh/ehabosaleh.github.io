---
title: "Diary"
permalink: /diary/
---

{% assign posts = site.categories.diary %}
{% for post in posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}
