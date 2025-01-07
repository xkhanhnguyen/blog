---
layout: default
title: Notes
---

# Notes

Browse my collection of notes:
<ul>
  {% for note in site.notes %}
    <li><a href="{{ note.url }}">{{ note.title }}</a></li>
  {% endfor %}
</ul>
