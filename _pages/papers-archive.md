---
layout: single
title: "Publications"
collection: papers
permalink: /papers/
redirect_from: /preprints/
author_profile: false
---

{% assign postsInYear = site.papers | group_by_exp: 'post', 'post.date | date: "%Y"' %}
{% assign totalPapers = site.papers | size %}
{% assign totalPreprints = site.preprints | size %}

<ul class="taxonomy__index">
  {% if site.preprints != null %}
  <li>
    <a href="#Preprints">
      <strong>Preprints</strong> <span class="taxonomy__count">{{ totalPreprints }}</span>
    </a>
  </li>
  {% endif %}
  {% for year in postsInYear reversed %}
    <li>
      <a href="#{{ year.name }}">
        <strong>{{ year.name }}</strong> <span class="taxonomy__count">{{ year.items | size }}</span>
      </a>
    </li>
  {% endfor %}
  <li>
    <a href="#Total">
      <strong>Total</strong> <span class="taxonomy__count">{{ totalPreprints | plus: totalPapers }}</span>
    </a>
  </li>
</ul>

{% if site.preprints != null %}
<section id="Preprints" class="taxonomy__section">
  <h2 class="archive__subtitle">In the Pipeline Preprints</h2>
  <div class="entries-{{ page.entries_layout | default: 'list' }}">
    {% for post in site.preprints %}
      {% include archive-paper.html type=page.entries_layout %}
    {% endfor %}
  </div>
  <a href="#page-title" class="back-to-top">{{ site.data.ui-text[site.locale].back_to_top | default: 'Back to Top' }} &uarr;</a>
</section>
{% endif %}

{% for year in postsInYear reversed %}
  <section id="{{ year.name }}" class="taxonomy__section">
    <h2 class="archive__subtitle">{{ year.name }}</h2>
    <div class="feature__wrapper">
      {% for post in year.items %}
        {% include archive-paper.html type=page.entries_layout %}
      {% endfor %}
    </div>
    <a href="#page-title" class="back-to-top">{{ site.data.ui-text[site.locale].back_to_top | default: 'Back to Top' }} &uarr;</a>
  </section>
{% endfor %}
