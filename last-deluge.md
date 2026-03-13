---
layout: page
title: Ostatni potop
lang: en
ref: project
nav_key: project
permalink: /last-deluge/
seo_title: "Ostatni potop | Literary project"
description: "Overview of the Ostatni potop book project: concept, world tone, supporting materials, and current status."
lead: "Heist fantasy novel project."
---

<section class="landing-section" aria-labelledby="book">
  <h2 id="book" class="SubSection">About the book</h2>
  <p>“Ostatni potop” [The Last Flood] is a novel project set in the kingdom of Parvaldenia. The story centers on a group of friends entangled in a conspiracy that threatens to destroy the entire kingdom.</p>
</section>

<section class="landing-section" aria-labelledby="world">
  <h2 id="world" class="SubSection">About the world</h2>
  <p>The world of Noricia is built in layers: through the core narrative, chronicles, legends, and songs. The tone is literary, restrained, and serious, balancing myth with history.</p>
</section>

<section class="landing-section" aria-labelledby="materials">
  <h2 id="materials" class="SubSection">Fragments and materials</h2>
  <p>The website publishes source materials, primarily from ancient times. Whenever possible, I add explanations and contextualize them. Excerpts and additions to the novel project will also be posted. Without revealing any details about the novel, of course.</p>
  {% assign chapter_excerpt = site.posts | where: "ref", "ostatni-potop-one" | where: "lang", page.lang | first %}
  {% if chapter_excerpt %}
  <p><a class="text-link" href="{{ chapter_excerpt.url | prepend: site.baseurl | prepend: site.url }}">Read an excerpt from the first chapter</a></p>
  {% endif %}
  <p><a class="text-link" href="{{ '/archive/' | prepend: site.baseurl | prepend: site.url }}">Go to the archive</a></p>
</section>

<section class="landing-section" aria-labelledby="status">
  <h2 id="status" class="SubSection">Project status</h2>
  <p>The project is actively being developed. The second phase of revisions is currently underway. An epilogue is also planned.</p>
<p>Statistics:</p>
<p>- 46 chapters</p>
<p>- approximately 2,000-3,000 words per chapter</p>
</section>
