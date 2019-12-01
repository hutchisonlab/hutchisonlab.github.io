---
title: Rapid Computational Discovery of Materials
layout: single
permalink: /materials-discovery/
---

We seek to use a variety of optimization methods to solve the rational "inverse design" of materials -- finding the chemical or molecular compositions with desired properties. The key challenge is that molecular and materials "design space" is _astronomically_ large, estimated to be 10<sup>60</sup> stable small molecules alone, often with conflicting properties (e.g., balancing molecular size and solubility).

<img src="/images/screeningpipeline.png" alt="materials screening pipeline" width="128px"/>{: .align-right}
Our work so far has demonstrated the speed and efficiency of genetic algorithms to find polymers and oligomers with desired properties using quantum chemical predictions. We seek to expand this work to properties including polymer morphology, energy storage, metal organic frameworks and more.

We also seek to accelerate our methods using [machine learning](/machine-learning) methods as fast approximations of computationally-intensive quantum chemical methods. The GA methods can, at the same time, generate new candidates for diverse data sets and accurate training data for ML methods.

## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = site.papers | where:"categories","Materials Discovery" | sort: 'date' | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
