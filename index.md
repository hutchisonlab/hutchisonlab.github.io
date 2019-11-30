---
title: Evolving Molecular Materials Lab
date: 2019-08-28T12:13:40+00:00
author: Geoff Hutchison
layout: single
share: false
related: false
num_posts: 8
---

{% include figure image_path="/images/people/Jan-2019.jpg" alt="Hutchison Research Group" %}

The Hutchison research group in the [Department of Chemistry](//chem.pitt.edu/) at the [University of Pittsburgh](//pitt.edu/) develops new materials, as well as functional microscale and nanoscale devices. We focus on building electronic materials from molecular subunits, both organic and inorganic, using a variety of techniques to rationally design the desired properties. This encompasses chemical synthesis, characterization (both physical and chemical), combined with theoretical modeling and simulation.

We also develop useful open source chemistry software, including the widely-used [Avogadro](//avogadro.cc/) molecular editor and [Open Babel](//openbabel.org/), the chemical toolbox, and the [Pitt Quantum Repository](//pqr.pitt.edu/).

<h2 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent News" }}</h2>

<div class="grid__wrapper">
  {% assign num_posts = 0 %}
  {% for post in site.posts %}
    {% if num_posts < page.num_posts %}
    {% endif %}
    {% assign num_posts = num_posts | plus: 1 %}
  {% endfor %}
</div>
