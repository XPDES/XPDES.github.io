---
layout: page
title: Meetings
---

# Past Meetings

<div class="posts">
  {% for post in site.categories.meeting %}
    <h2 class="post-title">
      <span class="date">{{ post.date | date: "%b %d, %Y" }}</span>
      <a href="{{ post.url }}">{{ post.title }} at {{ post.loc }}</a>
    </h2>
  {% endfor %}
</div>
