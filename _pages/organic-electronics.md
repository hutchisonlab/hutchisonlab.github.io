---
title: Organic Electronics
date: 2015-05-27T22:36:58+00:00
layout: single
permalink: /organic-electronics/
---

We are studying the “rational” design of novel organic solar cell materials, including generating millions of candidate polymers in a computational database, combined with detailed experimental and theoretical study of charge transport. With collaborators, we also push to improve nano and microscale morphology to improve electrical conductivity. In both projects, we use our expertise in statistical analysis and optimization: understanding the fundamental structure/activity relationships in materials, even in the face of many important variables.

## Morphology

Our work on [charge transport](/charge-transport/) have allowed us to simulate and predict optimal nanoscale morphologies and properties needed for high power efficiency. Increasing nanoscale roughness, allowing for highly delocalized charge carriers, and minimizing charge traps are all important parameters.

## Energetics and Efficiency

We are using computational methods to drive an “evolutionary algorithm” and quickly locate conducting polymers with tailored band gaps and energetics. Our approach has created a modeling pipeline for filtering through millions of possible co-polymers. To date, we have discovered thousands of high-efficiency candidates and are analyzing trends and synthetic accessibility.


<div class="page__related">
<h2>Recent Publications:</h2>
  <div class="grid__wrapper">
    {% assign papers = site.papers | where:"category","Organic Electronics" %}
    {% for paper in site.papers limit:5 %}
      {% include archive-single.html %}
    {% endfor %}
  </div>
</div>
