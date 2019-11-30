---
title: Polarizable Drude Model with s-Type Gaussian or Slater Charge Density for General Molecular Mechanics Force Fields
date: 2018-10-03T18:46:27+00:00
author: Geoff Hutchison
layout: single
categories:
  - Conformers
  - Papers
header:
  teaser: /images/abstracts/2018-polarizable-drude.gif
citation: '_J. Chem. Theory Comp._ (**2018**) 14(11) 5553-5566.'
doi: //doi.org/10.1021/acs.jctc.8b00430
---

Mohammad Mehdi Ghahremanpour, Paul J van Maaren, Carl Caleman, Geoffrey R Hutchison, David Van der Spoel &#8220;{{ page.title }}.&#8221; {{page.citation}} [DOI]({{page.doi}}){: .btn .btn--info} [Preprint](https://doi.org/10.26434/chemrxiv.7035881.v1){: .btn .btn--success}

<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right}
Gas-phase electric properties of molecules can be computed routinely using wave function methods or density functional theory (DFT). However, these methods remain computationally expensive for high-throughput screening of the vast chemical space of virtual compounds. Therefore, empirical force fields are a more practical choice in many cases, particularly since force field methods allow one to routinely predict the physicochemical properties in the condensed phases. This work presents Drude polarizable models, to increase the physical realism in empirical force fields, where the core particle is treated as a point charge and the Drude particle is treated either as a 1s-Gaussian or a ns-Slater (n = 1, 2, 3) charge density. Systematic parametrization to large high-quality quantum chemistry data obtained from the open access Alexandria Library (https://doi.org/10.5281/zenodo.1004711) ensures the transferability of these parameters. The dipole moments and isotropic polarizabilities of the isolated molecules predicted by the proposed Drude models are in agreement with experiment with accuracy similar to DFT calculations at the B3LYP/aug-cc-pVTZ level of theory. The results show that the inclusion of explicit polarization into the models reduces the root-mean-square deviation with respect to DFT calculations of the predicted dipole moments of 152 dimers and clusters by more than 50%. Finally, we show that the accuracy of the electrostatic interaction energy of the water dimers can be improved systematically by the introduction of polarizable smeared charges as a model for charge penetration.
