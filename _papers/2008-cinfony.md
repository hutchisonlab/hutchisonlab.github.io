---
title: 'Cinfony - combining Open Source cheminformatics toolkits behind a common interface'
date: 2008-12-03T13:43:57+00:00
author: Geoff Hutchison
layout: single
categories:
  - Cheminformatics
  - Papers
header:
  teaser: /images/abstracts/cinfony.gif
doi: //doi.org/10.1186/1752-153X-2-24
citation: "_Chem. Central J._ **2008** 2 art. 24."
---
Noel M. O&#8217;Boyle, Geoffrey R. Hutchison. “{{page.title}}.” {{page.citation}} [Open Access]({{page.doi}}).  
<!--more-->

<img alt="toc image" src="{{ page.header.teaser }}" width="300 px">{: .align-right}

## Background
Open Source cheminformatics toolkits such as OpenBabel, the CDK and the RDKit share the same core functionality but support different sets of file formats and forcefields, and calculate different fingerprints and descriptors. Despite their complementary features, using these toolkits in the same program is difficult as they are implemented in different languages (C++ versus Java), have different underlying chemical models and have different application programming interfaces (APIs).

## Results

We describe Cinfony, a Python module that presents a common interface to all three of these toolkits, allowing the user to easily combine methods and results from any of the toolkits. In general, the run time of the Cinfony modules is almost as fast as accessing the underlying toolkits directly from C++ or Java, but Cinfony makes it much easier to carry out common tasks in cheminformatics such as reading file formats and calculating descriptors.

## Conclusion

By providing a simplified interface and improving interoperability, Cinfony makes it easy to combine complementary features of OpenBabel, the CDK and the RDKit.
