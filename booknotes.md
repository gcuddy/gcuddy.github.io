---
layout: default
permalink: /notes/
title: Notes and Takeaways from Books I've Read
---

# Notes

Most of the learning I've done over the past few years has been through reading. This page summarizes my notes from these books.

I'm considering including my notes from theatre, film, and art. But for now, just books.

**This page will update as I add more.**

*To get the notes, click on any link.* You can sort by <a href="#rating" onclick="sortRating()">Rating</a>, <a href="#date" onclick="sortDate()">Date</a>, or <a href="#title" onclick="sortTitle()">Title</a>.

<hr>


<div id="rating">

{% assign sorted_rating = site.booknotes | sort:"rating" | reverse %}


  {% for booknote in sorted_rating %}
    <p id="book">
      <a class ="link b black dim f4" href="{{ booknote.url }}">
        {{ booknote.title }} by {{ booknote.author }}
      </a>
      <i>({{ booknote.rating }})</i>
      {{ booknote.desc }}
    </p>
  {% endfor %}

</div>

<div id="date" style="display: none;">

{% assign sorted_date = site.booknotes | sort:'date' | reverse %}

  {% for booknote in sorted_date %}
  <p>
    <a class ="link b black dim f4" href="{{ booknote.url }}">
      {{ booknote.title }} by {{ booknote.author }}
    </a>
    <i>({{ booknote.rating }})</i>
    {{ booknote.desc }}
  </p>
  {% endfor %}
</div>

<div id="title" style="display: none;">

{% assign sorted_title = site.booknotes | sort:"title" %}

  {% for booknote in sorted_title %}
  <p>
    <a class ="link b black dim f4" href="{{ booknote.url }}">
      {{ booknote.title }} by {{ booknote.author }}
    </a>
    <i>({{ booknote.rating }})</i>
    {{ booknote.desc }}
  </p>
  {% endfor %}
</div>

<div id="fiction" style="display: none;">

    {% for booknote in site.booknotes %}
      {% if booknote.category == "fiction" %}
      <p>
        <a class ="link b black dim f4" href="{{ booknote.url }}">
          {{ booknote.title }} by {{ booknote.author }}
        </a>
        <i>({{ booknote.rating }})</i>
        {{ booknote.desc }}
      </p>

      {% endif %}
    {% endfor %}

  </div>

<script>
function sortRating() {
  var rating = document.getElementById("rating");
  var date = document.getElementById("date");
  var title = document.getElementById("title");
  rating.style.display = "block";
  date.style.display = "none";
  title.style.display = "none";
}

function sortDate() {
  var rating = document.getElementById("rating");
  var date = document.getElementById("date");
  var title = document.getElementById("title");
  date.style.display = "block";
  rating.style.display = "none";
  title.style.display = "none";
}

function sortTitle() {
  var rating = document.getElementById("rating");
  var date = document.getElementById("date");
  var title = document.getElementById("title");
    rating.style.display = "none";
    date.style.display = "none";
    title.style.display = "block";
}


</script>
