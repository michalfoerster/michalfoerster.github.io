---
layout: page
title: Autor
lang: pl
ref: author
nav_key: author
permalink: /o-autorze/
seo_title: "Autor | Michał Foerster"
description: "Krótki biogram Michała Foerstera oraz informacje o autorskim świecie i projekcie Ostatni potop."
lead: "Piszę fantasy osadzone w autorskim świecie."
---

<section class="author-section" aria-labelledby="bio">
  <h2 id="bio" class="SubSection">Michał Foerster</h2>
  <div class="intro-row">
    <img class="site-avatar" src="{{ '/assets/img/avatar.jpg' | prepend: site.baseurl | prepend: site.url }}" alt="Królewna Sōline" />
    <p class="intro-text">Autor projektu „Ostatni potop” oraz świata Norycji. Konsekwentnie buduje spójne uniwersum, w którym narracja powieściowa spotyka się z materiałami kronikarskimi, pieśniami i legendami.</p>
  </div>
</section>

<section class="landing-section" aria-labelledby="warsztat">
  <h2 id="warsztat" class="SubSection">Praca nad światem i książką</h2>
  <p>Tworzę powieść heist fantasy "Ostatni potop". Fabuła rozgrywa się w świecie, z którym można się zapoznać dzięki publikowanym tekstom źródłowym i dodatkom.</p>
  <p><a class="text-link" href="{{ '/ostatni-potop/' | prepend: site.baseurl | prepend: site.url }}">Zobacz stronę projektu „Ostatni potop”</a></p>
</section>

<section class="landing-section" aria-labelledby="kontakt">
  <h2 id="kontakt" class="SubSection">Kontakt</h2>
  <p>
    <a id="kontakt-mail-link" class="text-link" href="#" rel="nofollow">Pokaż adres e-mail</a>
  </p>
  <noscript>
    <p>Włącz JavaScript, aby wyświetlić adres e-mail.</p>
  </noscript>
</section>

<script>
  (function () {
    var link = document.getElementById("kontakt-mail-link");
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
