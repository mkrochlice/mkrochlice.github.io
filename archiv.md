---
layout: default
title: Archiv příspěvků
---

<h1>Archiv príspěvků</h1>

<ul>
{% for post in site.posts %}
    <li>{{ post.date | date: "%d. %m. %Y" }} - <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
