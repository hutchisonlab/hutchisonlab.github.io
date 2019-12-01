---
title: Designer Defects and Organic Charge Transport
layout: single
permalink: /charge-transport/
---

Our group seeks to understand the fundamental properties of molecular electronic materials in order to produce
new materials with higher charge mobility and conductivity, resulting in more efficient devices, including
organic solar cells, light emitting diodes, flexible electronics, sensors, batteries, etc.

To do this, we combine experimental investigation of monolayer and nanoscale transistors with designed defects: both in terms of the type and concentration of defects. The combined experimental and computational research will enable greater understanding of charge transport in molecular materials.s

## Experiment

We synthesize a range of _inorganic_ semiconducting complexes, such as metal phthalocyanines, as well as organic oligomers and polymers. We can tailor the relative electronic structure and concentrations of intentional designer defects. We fabricate our own chips and perform detailed device-level electrical characterization of the materials.

We also study nanoscale performance of devices using atomic force microscopy, including conductive-probe, electrostatic-force microscopy (local dielectric constant), and scanning-Kelvin probe microscopy.

## Theory and Simulation

Our goal is to scale down our experimental transistors and scale up our simulations to provide a 1:1 correspondence between experiment and theory, benefiting both communities. So far, our code can easily handle micron-scale devices. We have demonstrated the exact distribution of charged and neutral defects in realistic transistors and the effect of Coulomb interactions on carrier trajectories. Results correlate extremely well with experiments.

## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = site.papers | where:"categories","Charge Transport" | sort: 'date' | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
