---
layout: page
title: People
---

# People Involved with XPDES

XPDES brings together researchers from several institutes.

## Georgia Institute of Technology

<ul>
{% for page in site.pages %}
   {% if page.tags == 'gatech' %}
      <li><a href='{{site.url}}{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>

## Lawrence Livermore National Laboratory

<ul>
{% for page in site.pages %}
   {% if page.tags == 'llnl' %}
      <li><a href='{{site.url}}{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>

## Rensselaer Polytechnic Institute

<ul>
{% for page in site.pages %}
   {% if page.tags == 'rpi' %}
      <li><a href='{{site.url}}{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>

## University of Illinois at Urbana-Champaign

<ul>
{% for page in site.pages %}
   {% if page.tags == 'uiuc' %}
      <li><a href='{{site.url}}{{page.url}}'>{{page.title}}</a></li>
   {% endif %}
{% endfor %}
</ul>
