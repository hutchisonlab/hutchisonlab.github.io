---
title: Understanding Conformational Entropy in Small Molecules
date: 2021-3-24
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Conformers
header:
  teaser: /images/abstracts/2021-conformer-entropy.png
doi: ./doi.org/10.1021/acs.jctc.0c01213
citation: _J. Chem. Theory Comput._ **2021**, 17, 4, 2099–2106
---
Leung Sing Chan, Garrett Morris, Geoffrey R. Hutchison. "{{ page.title }}​" {{page.citation}} [DOI]({{ page.doi }}){: .btn .btn--info}

<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right} The calculation of the entropy of flexible molecules can be challenging, since the number of possible conformers grows exponentially with molecule size and many low-energy conformers may be thermally accessible. Different methods have been proposed to approximate the contribution of conformational entropy to the molecular standard entropy, including performing thermochemistry calculations with all possible stable conformations, and developing empirical corrections from experimental data. We have performed conformer sampling on over 120,000 small molecules generating some 12 million conformers, to develop models to predict conformational entropy across a wide range of molecules. Using insight into the nature of conformational disorder, our cross-validated physically-motivated statistical model can outperform common machine learning and deep learning methods, with a mean absolute error ≈4.8 J/mol•K, or under 0.4 kcal/mol at 300 K. Beyond predicting molecular entropies and free energies, the model implies a high degree of correlation between torsions in most molecules, often as- sumed to be independent. While individual dihedral rotations may have low energetic barriers, the shape and chemical functionality of most molecules necessarily correlate their torsional degrees of freedom, and hence restrict the number of low-energy conformations immensely. Our simple models capture these correlations, and advance our understanding of small molecule conformational entropy.
