---
layout: page
title: Ostatni potop
lang: en
ref: project
nav_key: project
permalink: /last-deluge/
seo_title: "Ostatni potop | Literary project"
description: "Overview of the Ostatni potop book project: concept, world tone, supporting materials, and current status."
lead: "A heist fantasy about conspiracy, friendship, and a kingdom on the brink of collapse."
---

<section class="landing-section" aria-labelledby="book">
  <h2 id="book" class="SubSection">About the book</h2>
  <p>“Ostatni potop” [The Last Flood] is a novel project set in the kingdom of Parvaldenia. The story centers on a group of friends entangled in a conspiracy that threatens to destroy the entire kingdom.</p>
</section>

<section class="landing-section" aria-labelledby="world">
  <h2 id="world" class="SubSection">About the world</h2>
<p>Parvaldenia. An island whose kings must heed the advice of the all-powerful Guild of Alchemists and spies tasked with protecting the people from monsters. For centuries, it has been submerged by flood after flood. The coming one may be its last.</p></section>

<section class="landing-section" aria-labelledby="postaci">
<h2 id="o-swiecie" class="SubSection">Heroes</h2>
<p><b>Fox</b> - A boy from the lowlands, a burglar. Drawn into matters bigger than he could have imagined.</p>
<p><b>Istvald</b> - The Mastermind. The Agent. The Madman. The leader of the team, who always has a plan B up his sleeve. But he can't always control his own emotions.</p>
<p><b>Elmede</b> - A girl who wanted to take part in an adventure. Instead, she found herself in the middle of a horror movie.</p>
</section>

<section class="landing-section" aria-labelledby="materials">
  <h2 id="materials" class="SubSection">Fragments and materials</h2>
  <p>The website publishes source materials, primarily from ancient times. Whenever possible, I add explanations and contextualize them. Excerpts and additions to the novel project will also be posted. Without revealing any details about the novel, of course.</p>
  {% assign chapter_excerpt = site.posts | where: "ref", "ostatni-potop-one" | where: "lang", page.lang | first %}
  {% if chapter_excerpt %}
  <p><a class="text-link" href="{{ chapter_excerpt.url | prepend: site.baseurl | prepend: site.url }}">Read an excerpt from the first chapter</a></p>
  {% endif %}
</section>

<section class="landing-section" aria-labelledby="status">
  <h2 id="status" class="SubSection">Project status</h2>
  <p>The project is actively being developed. The second phase of revisions is currently underway. An epilogue is also planned.</p>
<p>Statistics:</p>
<p>- 46 chapters</p>
<p>- approximately 2,000-3,000 words per chapter</p>
</section>
