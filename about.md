---
layout: page
title: Author
lang: en
ref: author
nav_key: author
permalink: /about/
seo_title: "Author | Michał Foerster"
description: "Short biography of Michał Foerster and notes on the Ostatni Potop literary project."
lead: "I write fantasy set in an original world."
---

<section class="author-section" aria-labelledby="bio">
  <h2 id="bio" class="SubSection">Michał Foerster</h2>
  <div class="intro-row">
    <img class="site-avatar" src="{{ '/assets/img/avatar.jpg' | prepend: site.baseurl | prepend: site.url }}" alt="Author portrait of Michał Foerster" />
    <p class="intro-text">Author of the literary project “Ostatni Potop” [The Last Flood] and the world of Noricia. I build a coherent setting where the central novel is expanded through chronicles, songs, and legends.</p>
  </div>
</section>

<section class="landing-section" aria-labelledby="practice">
  <h2 id="practice" class="SubSection">Worldbuilding and narrative</h2>
  <p>I'm writing a heist fantasy novel, "Ostatni potop." The story takes place in a world explored through published source texts and supplements.</p>
  <p><a class="text-link" href="{{ '/last-deluge/' | prepend: site.baseurl | prepend: site.url }}">Open the “Ostatni Potop” project page</a></p>
</section>

<section class="landing-section" aria-labelledby="contact">
  <h2 id="contact" class="SubSection">Contact</h2>
  <p>
    <a id="author-email-link" class="text-link" href="#" rel="nofollow">Show email address</a>
  </p>
  <noscript>
    <p>Please enable JavaScript to reveal the email address.</p>
  </noscript>
</section>

<script>
  (function () {
    var link = document.getElementById("author-email-link");
    if (!link) return;
    var userCodes = [109, 105, 99, 104, 97, 108, 102, 111, 101, 114, 115, 116, 101, 114];
    var domainCodes = [103, 109, 97, 105, 108, 46, 99, 111, 109];
    var user = userCodes.map(function (code) { return String.fromCharCode(code); }).join("");
    var domain = domainCodes.map(function (code) { return String.fromCharCode(code); }).join("");
    var address = user + "@" + domain;
    link.setAttribute("href", ["mai", "lto:"].join("") + address);
    link.textContent = address;
  })();
</script>
