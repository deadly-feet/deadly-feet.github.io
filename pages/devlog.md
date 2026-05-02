---
layout: default
title: Devlogs
---

*Game Programmer and Tool Developer*

# Devlogs

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    - {{ post.date | date: "%d %b %Y" }}
  </li>
{% endfor %}
</ul>