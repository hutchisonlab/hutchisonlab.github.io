---
title: 'Confab: Systematic generation of diverse low-energy conformers'
date: 2011-03-16T13:29:52+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Conformers
  - Papers
doi: //doi.org/10.1186/1758-2946-3-8
citation: "_J. Cheminf._ **2011** _3_:8."
header:
  teaser: /images/abstracts/confab.gif
---
Noel M. O’Boyle, Tim Vandermeersch, Christopher J. Flynn, Anita R. Maguire, Geoffrey R. Hutchison. "{{ page.title }}" {{page.citation}} [DOI]({{ page.doi }})  
<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right}

## Background

Many computational chemistry analyses require the generation of conformers, either on-the-fly, or in advance. We present Confab, an open source command-line application for the systematic generation of low-energy conformers according to a diversity criterion.

## Results

Confab generates conformations using the &#8216;torsion driving approach&#8217; which involves iterating systematically through a set of allowed torsion angles for each rotatable bond. Energy is assessed using the MMFF94 forcefield. Diversity is measured using the heavy-atom root-mean-square deviation (RMSD) relative to conformers already stored. We investigated the recovery of crystal structures for a dataset of 1000 ligands from the Protein Data Bank with fewer than 1 million conformations. Confab can recover 97% of the molecules to within 1.5 Å at a diversity level of 1.5 Å and an energy cutoff of 50 kcal/mol.

## Conclusions

Confab is available from <http://confab.googlecode.com>

**Note:** Confab is now integrated directly into [Open Babel v2.4 and later](https://openbabel.org/)
