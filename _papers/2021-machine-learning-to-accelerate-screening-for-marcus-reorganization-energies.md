---
title: Machine learning to accelerate screening for Marcus reorganization energies
date: 2021-08-03
author: Geoff Hutchison
layout: single
categories:
  - Machine Learning
header:
  teaser: /images/abstracts/2021-ml-re.jpeg
doi: //doi.org/10.1063/5.0059682
citation: "_J. Chem. Phys._ 155, 054106 (**2021**)."
---

Omri D. Abarbanel, Geoffrey R. Hutchison. "{{ page.title }}​" {{page.citation}} [DOI]({{ page.doi }}){: .btn .btn--info} [Preprint](//doi.org/10.33774/chemrxiv-2021-db566-v2){: .btn .btn--success} [Data](/github.com/hutchisonlab/ReorganizationEnergy)

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right} While many machine learning (ML) methods, particularly deep neural networks, have been trained for density functional and quantum chemical energies and properties, the vast majority of these methods focus on single-point energies. In principle, such ML methods, once trained, offer thermochemical accuracy on par with density functional and wave function methods but at speeds comparable to traditional force fields or approximate semiempirical methods. So far, most efforts have focused on optimized equilibrium single-point energies and properties. In this work, we evaluate the accuracy of several leading ML methods across a range of bond potential energy curves and torsional potentials. The methods were trained on the existing ANI-1 training set, calculated using the ωB97X/6-31G(d) single points at nonequilibrium geometries. We find that across a range of small molecules, several methods offer both qualitative accuracy (e.g., correct minima, both repulsive and attractive bond regions, anharmonic shape, and single minima) and quantitative accuracy in terms of the mean absolute percent error near the minima. At the moment, ANI-2x, FCHL, and a new libmolgrid-based convolutional neural net, the Colorful CNN, show good performance.
