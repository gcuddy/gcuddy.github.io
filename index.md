---
layout: default
images:
  - image_path: /images/thumb/cuddy_headshot1.jpg
    title: Headshot 1
    link: /images/cuddy_headshot1.jpg
  - image_path: /images/thumb/cuddy_headshot2.jpg
    title: Headshot 2
    link: /images/cuddy_headshot2.jpg
  - image_path: /images/thumb/cuddy_headshot3.jpg
    title: Headshot 2
    link: /images/cuddy_headshot3.jpg
---

Hey, I'm Gus. I'm an actor.
{: .f3}

I am from Rochester, NY and am currently based in NYC.

## Headshot

  <a href="/images/cuddy_headshot.jpg">
    <img src="/images/thumb/cuddy_headshot.jpg" alt="Headshot"/>
  </a>

## Contact

**Ivy Rock Management**
Ann Kelly
(646) 418-5418
ivyrockmanagement@gmail.com

Find me on [Actor's Access](http://resumes.actorsaccess.com/guscuddy), [Twitter](http://twitter.com/guscuddy), and [Instagram](http://instagram.com/guscuddy). Or [email me](mailto:gus.cuddy@gmail.com) personally.

## Resume

(click to download)

<a href="/files/cuddy_resume.pdf"><img src="/images/cuddy_resume.jpg" alt="resume"/></a>

## More Headshots

(click for big)

<ul style="list-style:none; padding-left:0;" class="photo-gallery">
  {% for image in page.images %}
    <li style="padding-bottom:.5rem;">
      <a href="{{ image.link }}">
        <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
      </a>
    </li>
  {% endfor %}
</ul>

## More

[Click here](/a) for more photos of me acting.

I also write [plays](/plays) and [short essays](/blog), direct, and work on [other projects](/projects).
