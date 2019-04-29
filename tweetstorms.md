---
layout: default
permalink: /twitter/
title: "Twitter"
---

You can find me on Twitter [here](https://twitter.com/guscuddy).

Here's a collection of my tweetstorms:


<ul>
  {% for tweetstorm in site.tweetstorms %}
  <li>
    <h2 class="f4"> {{ tweetstorm.day }} - <a href="{{ tweetstorm.url }}">{{ tweetstorm.title }}</a> - <i><a class="link" href="{{ tweetstorm.tweet }}" target="_blank">(original)</a></i></h2>
    </li>
  {% endfor %}
</ul>
