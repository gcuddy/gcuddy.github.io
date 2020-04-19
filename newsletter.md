---
layout: home
permalink: /newsletter
---

<div id="intro" class="lh-title dib f1-ns f2-m f2">The Curtain</div>

Hey! I'd love to stay in touch.

The Curtain is my weekly newsletter, and I'd love to have you on the list. Each Tuesdsay I share what I'm thinking about in the world of culture and creativity, and curate the best links and esoterica I found during the week.

Sign up below:

<div class="pb2">
 <form name="email-capture" class="measure-wide br2-ns ba b--black-10 center" data-netlify="true">
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

You can always read [the full archive here](https://guscuddy.substack.com/archive).

The emails are sent from my personal email and you can reply directly or unsubscribe anytime.
