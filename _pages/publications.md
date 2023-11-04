---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
Gasparin M., Scarpa B., Stanghellini E. (202+). Omitting continuous covariates in binary regression models: implications for sensitivity and mediation analysis. [arXiv](https://arxiv.org/abs/2306.09969)
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
