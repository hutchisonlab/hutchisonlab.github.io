---
title: Evaluation of Thermochemical Machine Learning for Potential Energy Curves and Geometry Optimization
date: 2021-02-25T18:46:27+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Conformers
header:
  teaser: /images/abstracts/2021-ml-pes.png
doi: //doi.org/10.1021/acs.jpca.0c10147
citation: "_J. Phys. Chem. A_ (**2021**) _ASAP_."
---
Dakota L. Folmsbee, David R. Koes, Geoffrey R. Hutchison. "{{ page.title }}​" {{page.citation}} [DOI]({{ page.doi }}){: .btn .btn--info} [Preprint](//doi.org/10.26434/chemrxiv.13029437){: .btn .btn--success} [Data](//github.com/hutchisonlab/ml-benchmark)

<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right} While many machine learning (ML) methods, particularly deep neural networks, have been trained for density functional and quantum chemical energies and properties, the vast majority of these methods focus on single-point energies. In principle, such ML methods, once trained, offer thermochemical accuracy on par with density functional and wave function methods but at speeds comparable to traditional force fields or approximate semiempirical methods. So far, most efforts have focused on optimized equilibrium single-point energies and properties. In this work, we evaluate the accuracy of several leading ML methods across a range of bond potential energy curves and torsional potentials. The methods were trained on the existing ANI-1 training set, calculated using the ωB97X/6-31G(d) single points at nonequilibrium geometries. We find that across a range of small molecules, several methods offer both qualitative accuracy (e.g., correct minima, both repulsive and attractive bond regions, anharmonic shape, and single minima) and quantitative accuracy in terms of the mean absolute percent error near the minima. At the moment, ANI-2x, FCHL, and a new libmolgrid-based convolutional neural net, the Colorful CNN, show good performance.
