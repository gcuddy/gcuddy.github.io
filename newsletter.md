---
layout: home
permalink: /newsletter
active: newsletter
title: Newsletter
---

<div id="intro" class="lh-title dib f1-ns f2-m f2">The Curtain</div>

Hey! I'd love to stay in touch.

The Curtain is my weekly newsletter, and I'd love to have you on the list. Each Tuesdsay I share what I'm thinking about in the world of culture and creativity, and curate the best links and esoterica I found during the week.

Sign up below:

<div>
 <form id="my-form" name="email-capture" class="measure-wide br2-ns ba b--black-10 center" data-netlify="true" method="POST">
   <div class="cf">
   <input class="input-reset bn fl black bg-white pa3 lh-solid w-100 w-75-m w-80-l br2-ns br--left-ns" name="email" type="email" placeholder="Email" required>
   <button type="submit" class="button-reset fl pv3 tc bn bg-pers hover-pers-yellow white pointer w-100 w-25-m w-20-l br2-ns br--right-ns">Subscribe</button>
   </div>
 </form>

 <p class="js-success-message is-hidden f5" style="display: none; color:green; text-align: center;">Success! You'll receive your first email soon.</p>
</div>

<script>
  $("#my-form").submit(function(e) {
  e.preventDefault();

  var $form = $(this);
  $.post($form.attr("action"), $form.serialize()).then(function() {
    $("#my-form").hide();
    $(".js-success-message").show();
  });
});
 </script>

You can always read [the full archive here](https://guscuddy.substack.com/archive).

The emails are sent from my personal email and you can reply directly or unsubscribe anytime.

## What People Are Saying:

"I look forward to it every week and love the multi-pronged approach to absorbing artwork, theater and otherwise. It is rare and even if I don't always agree, I dig it."

"Your newsletter is like one of the highlights of my week." 