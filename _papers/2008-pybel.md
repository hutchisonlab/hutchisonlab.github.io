---
title: 'Pybel: A Python wrapper for the OpenBabel cheminformatics toolkit'
date: 2008-03-09T13:43:57+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Papers
header:
  teaser: /images/abstracts/pybel.gif
doi: //doi.org/10.1186/1752-153X-2-5
citation: "_Chem. Central J._ **2008** 2 art. 5."
---
Noel M. O&#8217;Boyle, Chris Morley, Geoffrey R. Hutchison. “{{page.title}}” {{page.citation}} [Open Access]({{page.doi}}).  
<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right}

## Background

Scripting languages such as Python are ideally suited to common programming tasks in cheminformatics such as data analysis and parsing information from files. However, for reasons of efficiency, cheminformatics toolkits such as the OpenBabel toolkit are often implemented in compiled languages such as C++. We describe Pybel, a Python module that provides access to the OpenBabel toolkit.

## Results

Pybel wraps the direct toolkit bindings to simplify common tasks such as reading and writing molecular files and calculating fingerprints. Extensive use is made of Python iterators to simplify loops such as that over all the molecules in a file. A Pybel Molecule can be easily interconverted to an OpenBabel OBMol to access those methods or attributes not wrapped by Pybel.

## Conclusion

Pybel allows cheminformaticians to rapidly develop Python scripts that manipulate chemical information. It is open source, available cross-platform, and offers the power of the OpenBabel toolkit to Python programmers.
