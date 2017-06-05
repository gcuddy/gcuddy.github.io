---
layout: default
permalink: /plays/
title: "PLAYS"
---

# Plays
{: .f2 .lh-title}

I'm working on two plays right now. They are both works-in-progress and the titles are working titles.

I do this as a thing on the side right now. But I enjoy it.

<div>
  {% for play in site.plays %}
    <h2 class="f4"><a href="{{ play.url }}">{{ play.title }}</a></h2>
    <p>{{ play.desc }}</p>
  {% endfor %}
</div>
