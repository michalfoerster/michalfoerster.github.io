---
layout: page
title: Ostatni potop
lang: pl
ref: project
nav_key: project
permalink: /ostatni-potop/
seo_title: "Ostatni potop | Projekt literacki"
description: "Opis projektu książkowego Ostatni potop: założenia, charakter świata, materiały i aktualny status prac."
lead: "Heist fantasy o spisku, przyjaźni i królestwie stojącym nad przepaścią"
---

<section class="landing-section" aria-labelledby="o-ksiazce">
  <h2 id="o-ksiazce" class="SubSection">O książce</h2>
  <p>„Ostatni potop” to projekt powieściowy rozgrywający się w królestwie Parvaldenii. Historia koncentruje się na grupie przyjaciół zamieszanych w spisek, którego stawką jest zniszczenie całego królestwa.</p>
</section>

<section class="landing-section" aria-labelledby="o-swiecie">
  <h2 id="o-swiecie" class="SubSection">O świecie</h2>
<p>Parvaldenia. Wyspa, której królowie muszą liczyć się ze zdaniem wszechwładnego Cechu Alchemików i szpiegami mającymi za zadanie bronić ludzi przed potworami. Od stuleci zatopiana przez kolejne potopy. Ten, który nadchodzi może być jej ostatnim. </p></section>

<section class="landing-section" aria-labelledby="postaci">
  <h2 id="o-swiecie" class="SubSection">Bohaterowie</h2>
<p><b>Lis</b> - Chłopak z nizin, włamywacz. Wciągnięty w sprawy większe, niż mógłby sobie wyobrazić.</p>
<p><b>Istvald</b> - Mózg. Agent. Wariat. Dowódca ekipy, który zawsze ma plan B w zanadrzu. Ale nie zawsze radzi sobie z własnymi emocjami.</p>
<p><b>Elmede</b> - Dziewczyna, która chciała wziąć udział w przygodzie. Trafiła zaś w sam środek horroru.</p>
</section>

<section class="landing-section" aria-labelledby="fragmenty">
  <h2 id="fragmenty" class="SubSection">Fragmenty i materiały</h2>
  <p>Na stronie publikowane są materiały źródłowe, głównie z zamierzchłych czasów. W ramach możliwości dodaję objaśnienia i tłumaczę ich kontekst. Zamieszczane będą również fragmenty i dodatki do projektu "Ostatni potop". Oczywiście, bez zdradzania szczegółów powieści.</p>
  {% assign chapter_excerpt = site.posts | where: "ref", "ostatni-potop-one" | where: "lang", page.lang | first %}
  {% if chapter_excerpt %}
  <p><a class="text-link" href="{{ chapter_excerpt.url | prepend: site.baseurl | prepend: site.url }}">Przeczytaj fragment pierwszego rozdziału</a></p>
  {% endif %}
</section>

<section class="landing-section" aria-labelledby="status">
  <h2 id="status" class="SubSection">Status projektu</h2>
  <p>Projekt jest aktywnie rozwijany. Obecnie trwa druga faza poprawek. W planach jest jeszcze epilog.</p>
<p>Statystyka:</p>
<p>- 46 rozdziałów</p>
<p>- około 2-3 tys. słów na rozdział</p>
</section>
