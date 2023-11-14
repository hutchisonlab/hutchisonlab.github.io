---
title: Determining Best Practices for Using Genetic Algorithms in Molecular Discovery
date: 2023-09-01
authors: "Brianna L. Greenstein, Danielle C. Elsey, Geoffrey R. Hutchison"
layout: single
categories:
  - Organic Electronics
  - Materials Discovery
  - Genetic Algorithms
header:
  teaser: /images/abstracts/2023-GA-scheme.png
doi: //doi.org/10.1063/5.0158053
citation: "_J. Chem. Phys._ 2023, 159, 091501"
---
{{ page.authors }}. "{{ page.title }}" {{page.citation}} [Online]({{ page.doi }})

<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right} Genetic algorithms (GAs) are a powerful tool to search large chemical spaces for inverse molecular design. However, GAs have multiple hyperparameters that have not been thoroughly investigated for chemical space searches. In this tutorial, we examine the general effects of a number of hyperparameters, such as population size, elitism rate, selection method, mutation rate, and convergence criteria, on key GA performance metrics. We show that using a self-termination method with a minimum Spearman’s rank correlation coefficient of 0.8 between generations maintained for 50 consecutive generations along with a population size of 32, a 50% elitism rate, three-way tournament selection, and a 40% mutation rate provides the best balance of finding the overall champion, maintaining good coverage of elite targets, and improving relative speedup for general use in molecular design GAs.