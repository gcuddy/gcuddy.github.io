---
layout: default
permalink: /a
title: "ACTING"
images:
  - image_path: /images/a/small/moon.jpg
    title: A Moon for the Misbegotten
    link: /images/a/moon.jpg
  - image_path: /images/a/small/skin1.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin1.jpg
  - image_path: /images/a/small/skin2.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin2.jpg
  - image_path: /images/a/small/skin3.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin3.jpg
  - image_path: /images/a/small/skin4.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin4.jpg
  - image_path: /images/a/small/skin5.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin5.jpg
  - image_path: /images/a/small/skin6.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin5.jpg
  - image_path: /images/a/small/skin7.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin6.jpg
  - image_path: /images/a/small/skin8.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin8.jpg
  - image_path: /images/a/small/skin9.jpg
    title: The Skin of Our Teeth
    link: /images/a/skin9.jpg
  - image_path: /images/a/small/waptp1.jpg
    title: We Are Proud to Present a Presentation About the Herero of Namibia, Formerly Known as South West Africa, From the German Sudwestafrika, Between the Years 1884-1915
    link: /images/a/waptp1.jpg
  - image_path: /images/a/small/waptp2.jpg
    title: We Are Proud to Present a Presentation About the Herero of Namibia, Formerly Known as South West Africa, From the German Sudwestafrika, Between the Years 1884-1915
    link: /images/a/waptp2.jpg
  - image_path: /images/a/small/waptp3.jpg
    title: We Are Proud to Present a Presentation About the Herero of Namibia, Formerly Known as South West Africa, From the German Sudwestafrika, Between the Years 1884-1915
    link: /images/a/waptp3.jpg
  - image_path: /images/a/small/waptp4.jpg
    title: We Are Proud to Present a Presentation About the Herero of Namibia, Formerly Known as South West Africa, From the German Sudwestafrika, Between the Years 1884-1915
    link: /images/a/waptp4.jpg
  - image_path: /images/a/mud.jpg
    title: Mud
    link: /images/a/mud.jpg

---

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
