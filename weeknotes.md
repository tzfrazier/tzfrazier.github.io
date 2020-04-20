---
layout: page
title: Weeknotes
permalink: /weeknotes/
---
<ul>
  {% for post in site.posts %}
    {% if post.tags contains 'Weeknotes' %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
