---
layout: default
title: Gus Cuddy - Actor, writer, director
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

<h1 class="f3-ns f2">Gus Cuddy</h1>

<a href="/images/cuddy_headshot3.jpg">
  <img src="/images/thumb/cuddy_headshot3.jpg" class ="w-50" alt="Headshot"/>
</a>


Hey, I'm **Gus**.  I'm an [actor](/resume), writer, and director.

This is my personal website. It contains my [pictures and resume](/resume), my writing, and some of my other favorite things. Take a look around.

I was born in Davis, CA, grew up in Rochester, NY, and currently live in **Brooklyn, NY**. I'm of Armenian, Lebanese, Egyptian and Irish descent. But identity is complicated.

The best ways to contact me are via [email](mailto:gus.cuddy@gmail.com) or [twitter](http://twitter.com/guscuddy). [Instagram](http://instagram.com/guscuddy) works too. Also find me on [Actor's Access](http://resumes.actorsaccess.com/guscuddy) and [Backstage](http://backstage.com/u/guscuddy). See my [Resume](/resume) for acting inquiries.

I send out a weekly newsletter on Tuesdays called ["the curtain"](http://guscuddy.substack.com), and I recommend you subscribe. It's one of the best ways to keep in touch with me. I discuss theatre, media and technology, anything else I'm learning about, what I'm reading/watching, and personal updates. [Sign up by clicking here](http://guscuddy.substack.com) or entering your email below.

<div class="form-container pv2">

<form name="submit-to-google-sheet" class="mw7">
  <div class="cf">
  <input class="f6 f5-l input-reset bn fl black bg-white pa3 lh-solid w-100 w-75-m w-80-l br2-ns br--left-ns" name="email" type="email" placeholder="Email" required>
  <button type="submit" class="f6 f5-l button-reset fl pv3 tc bn bg-animate bg-black hover-bg-red white pointer w-100 w-25-m w-20-l br2-ns br--right-ns">Subscribe</button>
  </div>
</form>

<p class="js-success-message is-hidden" style="display: none;">Success!</p>
<p class="js-error-message is-hidden" style="display: none;">Error!</p>

</div>

<script>
  const scriptURL = 'https://script.google.com/macros/s/AKfycbztKAnb0jXzNot8bvrAIhzCCTS5A_AuOq-1djh4gYd4i-8s2Ak/exec'
  const form = document.forms['submit-to-google-sheet']
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


<h1 class="f4">My philosophy of theatre and art</h1>

As an [actor](/resume) and theatre artist I have worked with amazing people and institutions, and learned so much from all of them. I believe that the wonderful people you meet along the way are a major part of what makes this worth doing.

I love bringing myself fully to a project, sinking my teeth into something complex, collaborating with others, going from zero to one, and creating something new and exciting. I believe in vulnerability, truth and authenticity. I believe theatre should always be exciting, never boring or deadly.

I'm always thinking about what the role of theatre is in the 21st century, what we can do to ensure its survival and, more than that, its democratization.

Finally, as an artist I believe in not being locked into any particular genre or form, that each form is a form unto itself, and that you should have free rein to make art in whatever form is most appropriate to an idea.

<!-- Questions like:

* How do we democratize theatre, improving accessibility and diversity?
* How do we make a truly great, exciting, electric live experience?
* How can theatre use the internet?
* How does theatre interact and define itself in relation to other narrative (and non-narrative) mediums?
* What are the nature of stories? Is theatre simply storytelling, or something else entirely? -->

<!-- <h1 class="f4">Subscribe to my newsletter</h1>

Enter your email below to keep up with what I do! You can read the archive of my weekly newsletter [here](https://guscuddy.substack.com/archive). *(And if the form isn't working, you can always subsrcibe by [clicking here](http://guscuddy.substack.com).)* -->
