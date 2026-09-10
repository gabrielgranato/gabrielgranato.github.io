---
permalink: /
layout: classic
title: "Gabriel Granato"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section class="profile-intro">
  <img class="profile-photo{% if site.author.avatar == 'profile.svg' %} is-placeholder{% endif %}" src="{{ site.author.avatar | prepend: '/images/' | relative_url }}" alt="{% if site.author.avatar == 'profile.svg' %}Gabriel Granato initials{% else %}Gabriel Granato{% endif %}" width="270" height="338">
  <div class="profile-text" markdown="1">

# Gabriel Granato

<p class="affiliation">Ph.D. student in Business and Public Policy<br>Haas School of Business, University of California, Berkeley</p>

My research lies at the intersection of development economics, political economy, and organizational economics. I study the political economy of development, with an emphasis on the organizational foundations of informal institutions: the local arrangements through which communities solve collective-action problems where formal state capacity is limited.

<p class="education">Before Berkeley, I earned an M.Sc. in Economics from PUC-Rio and a B.A. in Economics from IBMEC.</p>

<div class="profile-links"><span class="cv-placeholder">CV forthcoming</span><a href="mailto:gabrielgranato@berkeley.edu">Email</a><a href="https://twitter.com/gabrielsgranato">Twitter</a><a href="https://github.com/gabrielgranato">GitHub</a></div>

  </div>
</section>

<section aria-labelledby="research-heading">
  <div class="section-heading"><h2 id="research-heading">Research</h2><a href="{{ '/research/' | relative_url }}">All research &rarr;</a></div>
  {% include classic-research.html %}
</section>
