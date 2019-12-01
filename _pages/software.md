---
title: Open Source Science
layout: single
permalink: /software/
---

Since our group combines theoretical modeling and experiment, we believe strongly in sharing our simulation codes and other programs we develop internally. We are also involved in development of several open chemistry tools. We use these to facilitate our research and provide them as a benefit to the community in the hopes that others may find them useful. (We also hope that others may contribute changes to these programs back to the community as well.)

We firmly believe that the scientific method requires reproducibility of results. In the case of computational tools, this means that data and tools must be available for others to use. As such, we believe that generally, open source code is in the spirit of the overall scientific community. All of the tools created by our group are provided under open source licensing.

## Open Babel

<img src="/images/babel256.png" alt="Open Babel logo" width="128px"/>{: .align-right}
[Open Babel](//openbabel.org/) is an open chemistry toolbox, designed to speak the many languages of chemical data. It’s an open, collaborative project, allowing anyone to search, convert, analyze, or store data from molecular modeling, chemistry, biochemistry, or related areas.

Put simply, Open Babel makes developing a range of chemistry software extremely easy.

## Avogadro

<img src="/images/avogadro.png" alt="Avogadro logo" width="128px"/>{: .align-right}
[Avogadro](//avogadro.cc) is an advanced molecular editor/builder and visualization tool. It is intended to be flexible and extendable. “Everything is a plugin.” Avogadro offers a range of features including cross-platform use (Windows, Mac, Linux) in computational chemistry, molecular modeling, bioinformatics, materials science, etc. It offers a flexible rendering system and plugin architecture to add unique tools and analysis methods.

After starting at Pitt, Avogadro has been downloaded over 1,000,000 times worldwide, and has been translated into over 25 foreign languages.

_We are currently working with collaborators on the next generation of Avogadro v2. Stay tuned._

## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = site.papers | where:"categories","Cheminformatics" | sort: 'date' | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
