---
title: Evolving Molecular Materials Lab
author: Geoff Hutchison
layout: single
share: true
related: false
---

{% include figure image_path="/images/group/2021-group-photo.png" alt="Hutchison Research Group" %}

The Hutchison research group in the [Department of Chemistry](//chem.pitt.edu/) at the [University of Pittsburgh](//pitt.edu/) develops new materials, as well as functional microscale and nanoscale devices. We focus on building electronic materials from molecular subunits, both organic and inorganic, using a variety of techniques to rationally design the desired properties. This encompasses chemical synthesis, characterization (both physical and chemical), combined with theoretical modeling and simulation.

We also develop useful open source chemistry software, including the widely-used [Avogadro](//avogadro.cc/) molecular editor and [Open Babel](//openbabel.org/), the chemical toolbox, and the [Pitt Quantum Repository](//pqr.pitt.edu/).

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent News" }}</h3>

<div class="grid__wrapper">
  {% for post in site.posts limit: 4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
