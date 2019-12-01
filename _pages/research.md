---
title: Combining Experiment & Theory in Organic Electronic Materials
author: Geoff Hutchison
layout: single
permalink: /research/
share: false
---

Our group combines experimental and computational investigations to gain deep understanding of organic electronic materials. The bottom line is to efficiently design novel molecular materials with improved properties. Below are areas we are currently studying in our lab.

## Molecular Piezoelectrics

<img src="/images/abstracts/peptide-piezo.png" alt="peptide piezoelectric" width="128px"/>{: .align-right}
[Piezoelectric materials](/piezoelectrics) deform shape in response to an electric field and are used in everything from high-tech atomic force microscopes (AFM) to airbag impact sensors in cars. Our group is creating nanoscale piezoelectric materials with high deformation. Potential applications include energy generation and highly sensitive sensors. [Learn More...](/piezoelectrics)

## Organic Electronics

<img src="/images/photovoltaic.png" alt="organic electronics" width="128px"/>{: .align-right}
We are studying the &#8220;rational&#8221; design of novel organic electronic materials including generating millions of candidate polymers in a computational database, combined with detailed experimental and theoretical study of charge transport. With collaborators, we are also pushing to improve nano- and microscale morphology to improve electrical conductivity. Applications include efficient flexible transistors, solar cells, energy storage and more. [Learn More...](/organic-electronics)

## Charge Transport & Designer Defects

<img src="/images/3probe.jpg" alt="3-probe charge transport" width="128px"/>{: .align-right}
Our group is creating monolayer and nanoscale devices with designed defects: both in terms of the type and concentration of defects. The combined experimental and computational research will enable greater understanding of charge transport in molecular materials. [Learn More...](/charge-transport)

## Materials Discovery

<img src="/images/screeningpipeline.png" alt="materials screening pipeline" width="128px"/>{: .align-right}
We are driving the discovery of new materials through the use of rapid computational screening using quantum chemical methods. Through genetic algorithms and other screening methods, we seek molecules, polymers, and materials with new properties for experimental investigation. [Learn More...](/materials-discovery)

## Cheminformatics

Put simply, cheminformatics focuses on understanding how to efficiently represent chemistry, and particularly molecules to computers. From our development of [Open Babel](//openbabel.org) and other open source toolkits, we seek to push for faster and more accurate methods in cheminformatics. These tools allow us to generate massive computational data sets, run our materials discovery pipelines, and accelerate machine learning in chemistry. [Learn More...](/cheminformatics)

## Machine Learning & Data Science

We use statistical methods, data science, and a variety of machine learning methods to analyze our results and drive future research. Whether training fast neural networks to replicate computationally demanding quantum chemistry methods or using Bayesian optimization to rapidly find new conformers, we look for methods that help us finish research faster and better. [Learn More...](/machine-learning)

## Recent Publications

<div class="grid__wrapper">
  {% assign papers = site.papers | sort: 'date' | reverse %}
  {% for post in papers limit:8 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
