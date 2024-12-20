---
layout: archive
title: "PUBLICATIONS"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Papers under review/preprints
====
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
      <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Sepulveda, J. G., Glavind, S. T., and Faber, M. H., "Enhancements and Benchmarking of MCMC Algorithms for Subset Simulations in Structural Reliability", submitted to Elsevier, 2024.

* Nielsen, L., Glavind, S. T., and Faber, M. H., "On Course for Calamity? – on Knowledge and Memory in Capacity Building for Risk Governance", invited to Taylor & Francis special issue, 2024.

Journal papers
====
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
     <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Sepulveda, J. G., Glavind, S. T., and Faber, M. H., "Seismic reliability analysis using Subset Simulation enhanced with an explorative adaptive conditional sampling algorithm", Probabilistic Engineering Mechanics, vol. 78, pp. 103690, 2024 ([link](https://www.sciencedirect.com/science/article/pii/S0266892024001127)).

* Glavind, S. T., Sepulveda, J. G., and Faber, M. H., "On a simple scheme for systems modeling and identification using big data techniques", Reliability Engineering & System Safety, vol. 220, pp. 108219, 2022 ([link](https://www.sciencedirect.com/science/article/abs/pii/S0951832021006979)).

* Glavind, S. T., Brüske, H., Christensen, E. D, and Faber, M. H., "Bayesian probabilistic representation of complex systems: With application to wave load modeling", Computer-Aided Civil and Infrastructure Engineering, pp. 1-21, 2021 ([link](https://onlinelibrary.wiley.com/doi/10.1111/mice.12763))

* Glavind, S. T., and Faber, M. H., "A framework for offshore load environment modeling", Journal of Offshore Mechanics and Arctic Engineering, vol. 142, no. 2, pp. 021702, OMAE-19-1059, 2020 ([link](https://asmedigitalcollection.asme.org/offshoremechanics/article-abstract/142/2/021702/1065640/A-Framework-for-Offshore-Load-Environment?redirectedFrom=PDF)).

* Nielsen, L., Glavind, S. T., Qin, J., and Faber, M. H., "Faith and fakes – dealing with critical information in decision analysis", Civil Engineering and Environmental Systems, vol. 36, no. 1, pp. 32-54, 2019 ([link](https://www.tandfonline.com/doi/full/10.1080/10286608.2019.1615476)).

Peer reviewed conference/workshop papers
====
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %} 
  <li>    {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., Sepulveda, J. G., and Faber, M. H., "On big data analysis for damage detection", in Proceedings of the 13th International Conference on Structural Safety and Reliability (ICOSSAR 2021-2022), ICOSSAR2021-P0569, 2022.

* Glavind, S. T., Brüske, H., and Faber, M. H., "On normalized fatigue crack growth modeling", in Proceedings of the ASME 2020 39th International Conference on Ocean, Offshore and Arctic Engineering (OMAE2020), OMAE2020-18613, 2020 ([link](https://asmedigitalcollection.asme.org/OMAE/proceedings-abstract/OMAE2020/84324/V02AT02A037/1092628)).

* Glavind, S. T., Sepulveda, J. G., Qin, J., and Faber, M. H., "Systems modeling using big data analysis techniques and evidence", in Proceedings of the IEEE 2019 4th International Conference on System Reliability and Safety (ICSRS2019), ICSRS2019-R0119, 2019 ([link](https://ieeexplore.ieee.org/document/8987667)).

* Glavind, S. T., and Faber, M. H., "A framework for offshore load environment modeling", in Proceedings of the ASME 2018 37th International Conference on Ocean, Offshore and Arctic Engineering (OMAE2018), OMAE2018-77674, 2018 ([link](https://asmedigitalcollection.asme.org/OMAE/proceedings-abstract/OMAE2018/51272/V07BT06A006/274135)).

Theses/reports
====
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'thesis' %}
   <li>   {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., "Information-consistent systems modeling and analysis - with applications in offshore engineering", PhD thesis, Aalborg University, 2021 ([link](https://vbn.aau.dk/da/publications/information-consistent-systems-modeling-and-analysis-with-applica)).

* Glavind, S. T., "Vibration-based identification of mass changes using statistical learning theory", MSc thesis, Aarhus University, 2016.
