---
title: Assessing conformer energies using electronic structure and machine learning methods
date: 2020-07-09T18:46:27+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Conformers
  - Preprints
header:
  teaser: /images/abstracts/2020-ConformersBenchmark.png
doi: //doi.org/10.1002/qua.26381
citation: "_Int. J. Quantum Chem._ (**2020**) _122_ e26381."
---
Dakota Folmsbee, Geoffrey R. Hutchison. "{{ page.title }}​" {{page.citation}} [DOI]({{ page.doi }}){: .btn .btn--info} [Preprint](//doi.org/10.26434/chemrxiv.11920914){: .btn .btn--success} [Data](//github.com/ghutchis/conformer-benchmark)

<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right} We have performed a large-scale evaluation of current computational methods, including conventional small-molecule force fields, semiempirical, density functional, ab initio electronic structure methods, and current machine learning (ML) techniques to evaluate relative single-point energies. Using up to 10 local minima geometries across ~700 molecules, each optimized by B3LYP-D3BJ with single-point DLPNO-CCSD(T) triple-zeta energies, we consider over 6,500 single points to compare the correlation between different methods for both relative energies and ordered rankings of minima. We find promise from current ML methods and recommend methods at each tier of the accuracy-time tradeoff, particularly the recent GFN2 semiempirical method, the B97-3c density functional approximation, and RI-MP2 for accurate conformer energies. The ANI family of ML methods shows promise, particularly the ANI-1ccx variant trained in part on coupled-cluster energies. Multiple methods suggest continued improvements should be expected in both performance and accuracy.
