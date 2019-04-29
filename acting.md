---
layout: default
permalink: /a
title: "Acting"
---

# Acting

Grab my [Headshot](/images/cuddy_headshot.jpg) & [Resume](/files/cuddy_resume.pdf).
{: .f4}

I love acting. It's the thing I enjoy most. Here are some pictures from some of
my favorite performances (click for big versions):

<ul style="list-style:none; padding-left:0;" class="photo-gallery">
  {% for image in page.images %}
    <li style="padding-bottom:.5rem;">
      <a href="{{ image.link }}">
        <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
      </a>
    </li>
  {% endfor %}
</ul>
