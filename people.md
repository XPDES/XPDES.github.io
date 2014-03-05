---
layout: page
title: People
---

# People Involved with XPDES

XPDES brings together researchers from many different institutes.

## Georgia Institute of Technology

<ul>
{% for page in site.pages %}
   {% if page.tags == 'gtech' %}
      <li><a href='{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>

## Lawrence Livermore National Laboratory

<ul>
{% for page in site.pages %}
   {% if page.tags == 'llnl' %}
      <li><a href='{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>

## Rensselaer Polytechnic Institute

<ul>
{% for page in site.pages %}
   {% if page.tags == 'rpi' %}
      <li><a href='{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>
