---
title: Organic Electronics
layout: single
permalink: /organic-electronics/
---

We are studying the “rational” design of novel organic solar cell materials, including generating millions of candidate polymers in a computational database, combined with detailed experimental and theoretical study of charge transport. With collaborators, we also push to improve nano and microscale morphology to improve electrical conductivity. In both projects, we use our expertise in statistical analysis and optimization: understanding the fundamental structure/activity relationships in materials, even in the face of many important variables.

## Morphology

Our work on [charge transport](/charge-transport/) have allowed us to simulate and predict optimal nanoscale morphologies and properties needed for high power efficiency. Increasing nanoscale roughness, allowing for highly delocalized charge carriers, and minimizing charge traps are all important parameters.

## Energetics and Efficiency

We are using computational methods to drive an “evolutionary algorithm” and quickly locate conducting polymers with tailored band gaps and energetics. Our approach has created a modeling pipeline for filtering through millions of possible co-polymers. To date, we have discovered thousands of high-efficiency candidates and are analyzing trends and synthetic accessibility.


## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = (site.papers | where:"categories","Organic Electronics" | sort: 'date') | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
