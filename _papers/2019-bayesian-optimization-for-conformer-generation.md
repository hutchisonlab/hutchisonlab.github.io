---
title: Bayesian optimization for conformer generation
date: 2019-05-21T18:46:27+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Conformers
  - Preprints
header:
  teaser: /images/abstracts/2019-bayesopt.png
doi: //doi.org/10.1186/s13321-019-0354-7
citation: '_J. Cheminf._ (**2019**) _11_ art. 32.'
---
Lucian Chan, Garrett Morris, Geoffrey R. Hutchison. "{{ page.title }}" {{page.citation}} [DOI]({{page.doi}}){: .btn .btn--info} [Preprint](https://doi.org/10.26434/chemrxiv.7228940.v4){: .btn .btn--success}

<!--more-->

<img alt="toc image" src="/images/abstracts/2019-bayesopt.png" width="300 px">{: .align-right} Generating low-energy molecular conformers is a key task for many areas of computational chemistry, molecular modeling and cheminformatics. Most current conformer generation methods primarily focus on generating geometrically diverse conformers rather than finding the most probable or energetically lowest minima. Here, we present a new stochastic search method called the Bayesian optimization algorithm (BOA) for finding the lowest energy conformation of a given molecule. We compare BOA with uniform random search, and systematic search as implemented in Confab, to determine which method finds the lowest energy. Energetic difference, root-mean-square deviation, and torsion fingerprint deviation are used to quantify the performance of the conformer search algorithms. In general, we find BOA requires far fewer evaluations than systematic or uniform random search to find low-energy minima. For molecules with four or more rotatable bonds, Confab typically evaluates 10<sup>4</sup> (median) conformers in its search, while BOA only requires 10<sup>2</sup> energy evaluations to find top candidates. Despite using evaluating fewer conformers, 20–40% of the time BOA finds lower-energy conformations than a systematic Confab search for molecules with four or more rotatable bonds.
