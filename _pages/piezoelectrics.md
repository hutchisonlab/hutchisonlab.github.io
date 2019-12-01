---
title: Electromechanical Materials
layout: single
permalink: /piezoelectrics/
category: Piezoelectrics
---

<img src="/images/helicene-toc-graphic.png" alt="helicene piezoelectric" width="300px"/>{: .align-right}
We investigate the electromechanical effects of individual molecular monolayers and organic polymers. In particular, our group has demonstrated that electric fields can drive mechanical changes in hydrogen bonds and force new conformations in polar molecules such as helicenes, peptides, and a wide variety of other species.

Piezoelectric materials deform shape in response to an electric field and are used in everything from high-tech atomic force microscopes (AFM) to airbag impact sensors in cars. Our group is creating nanoscale piezoelectric materials with high deformation. Potential applications include energy generation and highly sensitive sensors.

We use computational modeling to understand the connection between molecular structure and piezoelectric response. Based on these simulations, we have started developing “design rules” for synthetic organic piezoelectrics and are using a variety of experimental techniques to characterize monolayers and thin films to characterize this phenomenon.


## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = (site.papers | where:"categories","Piezoelectrics" | sort: 'date') | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
