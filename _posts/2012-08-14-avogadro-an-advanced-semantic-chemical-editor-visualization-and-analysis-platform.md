---
id: 693
title: 'Avogadro: An advanced semantic chemical editor, visualization, and analysis platform'
date: 2012-08-14T14:57:18+00:00
author: Geoff Hutchison
layout: post
guid: http://hutchison.chem.pitt.edu/?p=693
permalink: /2012/08/avogadro-an-advanced-semantic-chemical-editor-visualization-and-analysis-platform/
categories:
  - Cheminformatics
  - Publication
---
Marcus D Hanwell, Donald E Curtis, David C Lonie, Tim Vandermeersch, Eva Zurek, Geoffrey R Hutchison. &#8220;Avogadro: An advanced semantic chemical editor, visualization, and analysis platform.&#8221; _J. Cheminf._Â **2012**Â _4_:17.Â [Open Access.](http://dx.doi.org/10.1186/1758-2946-4-17)

<!--more-->

[<img class="alignleft size-medium wp-image-694" title="Avogadro Cover Art" src="https://i2.wp.com/pre.hutchison.chem.pitt.edu/wordpress/wp-content/uploads/2012/08/Avogadro-Cover-Art11-300x137.png?resize=300%2C137" alt="" width="300" height="137" data-recalc-dims="1" />](https://i1.wp.com/pre.hutchison.chem.pitt.edu/wordpress/wp-content/uploads/2012/08/Avogadro-Cover-Art11.png)

## Background

The Avogadro project has developed an advanced molecule editor and visualizer designed for cross-platform use in computational chemistry, molecular modeling, bioinformatics, materials science, and related areas. It offers flexible, high quality rendering, and a powerful plugin architecture. Typical uses include building molecular structures, formatting input files, and analyzing output of a wide variety of computational chemistry packages. By using the CML file format as its native document type, Avogadro seeks to enhance the semantic accessibility of chemical data types.

## Results

The work presented here details the Avogadro library, which is a framework providing a code library and application programming interface (API) with three-dimensional visualization capabilities; and has direct applications to research and education in the fields of chemistry, physics, materials science, and biology. The Avogadro application provides a rich graphical interface using dynamically loaded plugins through the library itself. The application and library can each be extended by implementing a plugin module in C++ or Python to explore different visualization techniques, build/manipulate molecular structures, and interact with other programs. We describe some example extensions, one which uses a genetic algorithm to find stable crystal structures, and one which interfaces with the PackMol program to create packed, solvated structures for molecular dynamics simulations. The 1.0 release series of Avogadro is the main focus of the results discussed here.

## Conclusions

Avogadro offers a semantic chemical builder and platform for visualization and analysis. For users, it offers an easy-to-use builder, integrated support for downloading from common databases such as PubChem and the Protein Data Bank, extracting chemical data from a wide variety of formats, including computational chemistry output, and native, semantic support for the CML file format. For developers, it can be easily extended via a powerful plugin mechanism to support new features in organic chemistry, inorganic complexes, drug design, materials, biomolecules, and simulations. Avogadro is freely available under an open-source license from [http://avogadro.openmolecules.net](http://avogadro.openmolecules.net/).