---
title: Cheminformatics
layout: single
permalink: /cheminformatics/
---

_If you've sketched out a molecule on a computer, you've performed some element of cheminformatics already._ Cheminformatics seeks to accurately represent the complexity of chemistry to computers.

We heavily use cheminformatics tools and software for [materials discovery](/materials-discovery) and [machine learning](/machine-learning).

## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = site.papers | where:"categories","Cheminformatics" | sort: 'date' | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
