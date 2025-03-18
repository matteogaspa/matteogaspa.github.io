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

Gasparin M., Ramdas A. (202+). Improving the statistical efficiency of cross-conformal prediction. [[arXiv]](https://arxiv.org/abs/2503.01495)

Gasparin M., Ramdas A. (202+). Conformal online model aggregation. [[arXiv]](https://arxiv.org/abs/2403.15527)

Gasparin M., Ramdas A. (202+). Merging uncertainty sets via majority vote. [[arXiv]](https://arxiv.org/abs/2401.09379)


## Journal articles
Gasparin M., Wang R., Ramdas A. (2025). Combining exchangeable p-values. Proceedings of the National Accademy of Science (PNAS), 122 (11) e2410849122. [[arXiv]](https://arxiv.org/abs/2404.03484)[[link]](https://doi.org/10.1073/pnas.2410849122)

Gasparin M., Scarpa B., Stanghellini E. (2025). Omitting continuous covariates in binary regression models: Implications for sensitivity and mediation analysis. Statistica Neerlandica, 79(1), e1236. [[arXiv]](https://arxiv.org/abs/2306.09969)[[link]](https://onlinelibrary.wiley.com/doi/full/10.1111/stan.12369)

Baritussio A., Giordani A.S., Basso C., Vicenzetto C., Lorenzoni G., Gasparin M., Iliceto S., Scarpa B., Gregori D., Marcolongo R., Caforio A.L.P. (2023). Uneventful COVID-19 Infection and Vaccination in a Cohort of Patients with Prior Myocarditis, Vaccines, 11(12):1742. [[link]](https://www.mdpi.com/2076-393X/11/12/1742)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
