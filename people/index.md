---
layout: default
title: People of XPDES
---

<h1>People Involved with XPDES</h1>
<ul>
{% for p in site.categories.people %}
   <li><a href='{{p.url}}'>{{p.title}}</a></li>
{% endfor %}
</ul>
