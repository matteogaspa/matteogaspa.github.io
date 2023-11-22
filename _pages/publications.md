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

Baritussio A., Giordani A.S., Basso C., Vicenzetto C., Lorenzoni G., Gasparin M., Iliceto S., Scarpa B., Gregori D., Marcolongo R., Caforio A.L.P., (2023). Uneventful COVID-19 Infection and Vaccination in a Cohort of Patients with Prior Myocarditis, Vaccines [link](https://www.mdpi.com/2076-393X/11/12/1742)


Gasparin M., Scarpa B., Stanghellini E. (202+). Omitting continuous covariates in binary regression models: implications for sensitivity and mediation analysis. [arXiv](https://arxiv.org/abs/2306.09969)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
