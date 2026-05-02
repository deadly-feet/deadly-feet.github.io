*Game Programmer and Tool Developer*

<ul>
{% raw %}{% for post in site.posts %}{% endraw %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    - {{ post.date | date: "%d %b %Y" }}
  </li>
{% raw %}{% endfor %}{% endraw %}
</ul>