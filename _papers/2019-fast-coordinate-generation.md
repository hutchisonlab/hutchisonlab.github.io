---
title: Fast, efficient fragment-based coordinate generation for Open Babel
date: 2019-08-01T18:46:27+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Conformers
  - Preprints
header:
  teaser: /images/abstracts/2019-ob-fragments.png
doi: //doi.org/10.1186/s13321-019-0372-5
citation: "_J. Cheminf._ (**2019**) _11_ art. 49."
---
Naruki Yoshikawa, Geoffrey R. Hutchison. "{{ page.title }}" {{page.citation}} [DOI]({{page.doi}}){: .btn .btn--info} [Preprint](https://doi.org/10.26434/chemrxiv.7791947.v2){: .btn .btn--success}

<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right} Rapidly predicting an accurate three dimensional geometry of a molecule is a crucial task for cheminformatics and across a wide range of molecular modeling. Consequently, developing a fast, accurate, and open implementation of structure prediction is necessary for reproducible cheminformatics research. We introduce a fragment-based coordinate generation implementation for Open Babel, a widely-used open source toolkit for cheminformatics. The new implementation improves speed and stereochemical accuracy, while retaining or improving accuracy of bond lengths, bond angles, and dihedral torsions. Input molecules are broken into fragments by cutting at rotatable bonds. The coordinates of fragments are set according to a fragment library, prepared from open crystallographic databases. Since the coordinates of multiple atoms are decided at once, coordinate prediction is accelerated over the previous rules-based implementation in Open Babel, as well as the widely-used distance geometry methods in RDKit. This new implementation will be beneficial for a wide range of applications, including computational property prediction in polymers, molecular materials and drug design.
