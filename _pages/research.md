---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
[Testing for Almost Stochastic Dominance](https://wonwoobae.github.io/files/ATSD_draft.pdf)
with [Yoon-Jae Whang](https://sites.google.com/site/whangyjhomepage/)

Work in Progress
[Diagnostic Global Game: Theory and Experiment](https://wonwoobae.github.io/files/DGG_draft.pdf)
with [Syngjoo Choi](https://sites.google.com/site/syngjoochoi/) and [Jeongbin Kim](https://sites.google.com/site/jbkimecon/)
