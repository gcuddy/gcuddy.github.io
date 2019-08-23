---
layout: default
permalink: /newsletter
---

I send out a weekly newsletter on Tuesdays called *[The Curtain](http://guscuddy.substack.com)*, and I recommend you subscribe. It's one of the best ways to keep in touch with me. Each week I share a short essay about what I'm thinking about, as well as links and notes from the week on theatre and culture. [Sign up by clicking here](http://guscuddy.substack.com) or entering your email below.

<div class="form-container pv2">

<form name="submit-to-google-sheet" class="mw7">
  <div class="cf">
  <input class="f6 f5-l input-reset bn fl black bg-white pa3 lh-solid w-100 w-75-m w-80-l br2-ns br--left-ns" name="email" type="email" placeholder="Email" required>
  <button type="submit" class="f6 f5-l button-reset fl pv3 tc bn bg-animate bg-black hover-bg-red white pointer w-100 w-25-m w-20-l br2-ns br--right-ns dim">Subscribe</button>
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

The emails are sent from my personal email and you can reply directly, or unsubscribe anytime.
