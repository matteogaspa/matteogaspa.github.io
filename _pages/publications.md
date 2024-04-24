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

## Preprints and working papers

Gasparin M., Wang R., Ramdas A. (202+). Combining exchangeable p-values. [(arXiv)](https://arxiv.org/abs/2404.03484)

Gasparin M., Ramdas A. (202+). Conformal online model aggregation. [(arXiv)](https://arxiv.org/abs/2403.15527)

Gasparin M., Ramdas A. (202+). Merging uncertainty sets via majority vote. [(arXiv)](https://arxiv.org/abs/2401.09379)

Gasparin M., Scarpa B., Stanghellini E. (202+). Omitting continuous covariates in binary regression models: implications for sensitivity and mediation analysis. [(arXiv)](https://arxiv.org/abs/2306.09969)


## Journal articles

Baritussio A., Giordani A.S., Basso C., Vicenzetto C., Lorenzoni G., Gasparin M., Iliceto S., Scarpa B., Gregori D., Marcolongo R., Caforio A.L.P. (2023). Uneventful COVID-19 Infection and Vaccination in a Cohort of Patients with Prior Myocarditis, Vaccines, 11(12):1742. [(link)](https://www.mdpi.com/2076-393X/11/12/1742)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
