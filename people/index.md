---
layout: default
title: People of XPDES
---

<ul>
{% for p in site.categories.people %}
   <h1><a href'{{p.url}}'>{{p.title}}</a></h1>
{% endfor %}
</ul>
