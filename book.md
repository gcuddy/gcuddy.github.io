---
layout: default
permalink: /book/
title: "BOOKS"
---

# Book Notes
{: .f2 .lh-title}

I collect books I've read here and write out my notes for them. They are usually long and disjointed. I'm also not good at differentiating between actual quotes and my own wording. Use at your own risk.

{% assign sorted = (site.books | sort: 'date') | reverse %}
<ul>
  {% for item in sorted %}
  <li>
    <a href="{{ item.url }}">{{ item.title }}</a> by {{ item.author }}
  </li>
  {% endfor %}
</ul>  
