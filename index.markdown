---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: home
---

# Welcome to My Blog

---
layout: default
title: Home
---

# Welcome to My Blog

This is a minimalist, dark-themed blog inspired by [adangnotes.com](https://www.adangnotes.com/).  

Explore the blog:  
- [About Me](about/)  
- [Notes](notes/)

## Recent Notes

<ul>
  {% for note in site.notes limit:5 %}
    <li>
      <a href="{{ note.url }}">{{ note.title }}</a>  
      <small>({{ note.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>

---
