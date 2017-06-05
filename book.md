---
layout: default
permalink: /book/
title: "BOOKS"
---

# Book Notes
{: .f2 .lh-title}

I collect books I've read here and write out my notes for them. They are usually long and disjointed. I'm also not good at differentiating between actual quotes and my own wording. Use at your own risk.

<p class="i f6">Sort by <a href="#" id="date" class="link b black dim">Newest</a> or <a href="#" id="name" class="link b black dim">Title</a>.

<div id="dateList">
{% assign sorted = (site.books | sort: 'date') | reverse %}
<ul>
  {% for item in sorted %}
  <li>
    <a href="{{ item.url }}">{{ item.title }}</a> by {{ item.author }}
  </li>
  {% endfor %}
</ul>  
</div>

<div id="nameList" class="dn">
{% assign sorted = (site.books | sort: 'title') %}
<ul>
  {% for item in sorted %}
  <li>
    <a href="{{ item.url }}">{{ item.title }}</a> by {{ item.author }}
  </li>
  {% endfor %}
</ul>  
</div>

<script>
window.onload = init;

var nameList = document.getElementById('nameList');
var dateList = document.getElementById('dateList');

function init() {
  var name = document.getElementById('name');
  var date = document.getElementById('date');
  var author = document.getElementById('author');
  name.onclick = sortByDate;
  date.onclick = sortByName;
  author.onclick = sortByAuthor;
}

function sortByName() {
  nameList.className="dn";
  dateList.className="";
}

function sortByDate() {
  nameList.className="";
  dateList.className="dn";
}
</script>
