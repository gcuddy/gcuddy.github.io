---
layout: home
title: Home
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
<div id="intro" class="lh-title dib f1-ns f2-m f2">hi, i'm gus.</div>

Welcome to my cyber home.  I [write](/blog), [act](/acting), and make theatre and movies.

Each week I send out a popular email called The Curtain. It's a weekly deep dive into the world of theatre, culture and creativity, featuring my own writing and a collection of links and notes. It's unlike any other newsletter I'm aware of.

Join 100+ subscribers and enter your email below:

<div class="pb2">
 <form name="email-capture" class="measure-wide br2-ns ba b--black-10 center" data-netlify="true" method="POST">
   <div class="cf">
   <input class="f6 f5-l input-reset bn fl black bg-white pa3 lh-solid w-100 w-75-m w-80-l br2-ns br--left-ns" name="email" type="email" placeholder="Email" required>
   <button type="submit" class="f6 f5-l button-reset fl pv3 tc bn bg-red white pointer w-100 w-25-m w-20-l br2-ns br--right-ns">Subscribe</button>
   </div>
 </form>

 <p class="js-success-message is-hidden" style="display: none; color:green; text-align: center;">Success!</p>
 <p class="js-error-message is-hidden" style="display: none; color:red; text-align: center;">Error!</p>
</div>

<script>
   const scriptURL = 'https://script.google.com/macros/s/AKfycbztKAnb0jXzNot8bvrAIhzCCTS5A_AuOq-1djh4gYd4i-8s2Ak/exec'
   const form = document.forms['email-capture']
   const successMessage = document.querySelector('.js-success-message')
   const errorMessage = document.querySelector('.js-error-message')

   form.addEventListener('submit', e => {
     e.preventDefault()
     fetch(scriptURL, { method: 'POST', body: new FormData(form)})
       .then(response => showSuccessMessage(response))
       .catch(error => showErrorMessage(error))
   })

   function showSuccessMessage (response) {
     console.log('Success!', response)
     setTimeout(() => {
       successMessage.style.display = "block";
     }, 500)
   }

   function showErrorMessage (error) {
     console.error('Error!', error.message)
     setTimeout(() => {
       errorMessage.style.display = "block";
     }, 500)
   }

 </script>

This website is a collection of my favorite stuff. My essays cover topics like culture, theatre, media, technology, society, art, and creativity. But most of my work centers around our interactions and relationships with culture. My most popular writing includes essays like [Cultural Nostalgia is Toxic](/nostalgia), [The Cult of Minimalism](/minimalism) and my 2019 essays on theatre's state of the [audience](/audience) and [criticism](/criticism).

To see the archive of all my writing, [click here](/blog).

Beyond writing, [I'm an actor](/acting) and director. I've been seen at the Humana Festival at Actor's Theatre of Louisville, Geva Theatre, Arizona Theatre Company, and many more. I love to dive into things and make exhilirating theatre with a room full of great collaborators.

I was born in Davis, CA, grew up in Rochester, NY, and currently live in **Brooklyn, NY**. I'm of Armenian, Lebanese, Egyptian and Irish descent. [But identity is complicated](/2dracism).

You can email me at gus (at) guscuddy.com

You can also find me on [Twitter](https://twitter.com/guscuddy) (where I'm active) and [Instagram](https://instagram.com/guscuddy) (where I'm less active).