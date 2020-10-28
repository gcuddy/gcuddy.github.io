---
layout: home
title: Home
active: home
---

<div id="intro" class="lh-title dib f1-ns f2-m f2">hi, i'm gus!</div>

Welcome to my web home.  I'm a [performer](/acting), [writer](/blog), theatremaker, and filmmaker.

---

Each Tuesday I send out an email newsletter called The Curtain. It's an exploration and analysis of culture, with a focus on theatre, film and other arts & media in the digital age.

You can subscribe by entering your email below:

<div>
 <form id="my-form" name="email-capture" class="measure-wide br2-ns ba b--black-10 center" data-netlify="true" method="POST">
   <div class="cf">
   <input class="input-reset bn fl black bg-white pa3 lh-solid w-100 w-75-m w-80-l br2-ns br--left-ns" name="email" type="email" placeholder="Email" required>
   <button type="submit" class="button-reset fl pv3 tc bn bg-pers hover-pers-yellow pers-yellow fw7 white pointer w-100 w-25-m w-20-l br2-ns br--right-ns">Subscribe</button>
   </div>
 </form>

 <p class="js-success-message is-hidden f4" style="display: none; color:green; text-align: center;">Success! You'll receive your first email soon.</p>
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
 
---

My short essays cover topics like culture, theatre, media, film, technology, society, art, and creativity. But most of my work centers around our interactions and relationships with culture, with the framing of my background in theatre, film and technology. My most popular writing includes essays like [Cultural Nostalgia is Toxic](/nostalgia), [The Cult of Minimalism](/minimalism) and my 2019 essays on theatre's state of the [audience](/audience) and [criticism](/criticism).

To see the archive of all my writing, [click here](/blog).

Beyond writing essays, [I'm an actor](/acting), playwright and director. I've been seen at the Humana Festival at Actor's Theatre of Louisville, Geva Theatre, Arizona Theatre Company, and many more. I love to dive into things and make exhilirating theatre with a room full of great collaborators.

I'm also a hobbyist web developer, designer and programmer.	

I was born in Davis, CA, grew up in Rochester, NY, and currently live in **Brooklyn, NY**. I'm of Armenian, Lebanese, Egyptian and Irish descent. [But identity is complicated](/2dracism).

You can email me at gus (at) guscuddy.com

You can also find me on [Twitter](https://twitter.com/guscuddy) (where I'm active) and [Instagram](https://instagram.com/guscuddy) (where I'm less active).

<p class="tc"><img class="w-100" src="/images/g2.jpeg"></p>
