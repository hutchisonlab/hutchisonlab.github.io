---
title: Teaching Computers Chemistry
layout: single
permalink: /machine-learning/
---

Machine Learning (ML) methods seek to use a variety of statistical tools, including neural networks, to analyze and train on massive data sets. Through both supervised and active learning methods, these ML models become increasingly accurate predictors of both computational and experimental data.

We draw on ML methods in our [materials discovery](/materials-discovery) research, seeking to meet the goal of accurate quantum chemical predictions with much faster speed than conventional methods that require hours or days of calculations.

## Recent Publications:

<div class="grid__wrapper">
  {% assign papers = site.papers | where:"categories","Machine Learning" | sort: 'date' | reverse %}
  {% for post in papers limit:4 %}
      {% include archive-single-date.html type="grid" %}
  {% endfor %}
</div>
