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

## Papers under review/preprints

{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
      <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., Brüske, H., Christensen, E. D, and Faber, M. H., "On systems modeling and context-specific model selection in offshore engineering", submitted to Computer-Aided Civil and Infrastructure Engineering, 2021.

* Glavind, S. T., Sepulveda, J. G., and Faber, M. H., "On a simple scheme for systems modeling and identification using big data techniques", submitted to Reliability Engineering & System Safety, 2021.

## Journal papers

{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
     <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., and Faber, M. H., "A framework for offshore load environment modeling", Journal of Offshore Mechanics and Arctic Engineering, vol. 142, no. 2, pp. 021702, OMAE-19-1059, 2020 ([link](https://asmedigitalcollection.asme.org/offshoremechanics/article-abstract/142/2/021702/1065640/A-Framework-for-Offshore-Load-Environment?redirectedFrom=PDF)).

* Nielsen, L., Glavind, S. T., Qin, J., and Faber, M. H., "Faith and fakes – dealing with critical information in decision analysis", Civil Engineering and Environmental Systems, vol. 36, no. 1, pp. 32-54, 2019 ([link](https://www.tandfonline.com/doi/full/10.1080/10286608.2019.1615476)).

## Peer reviewed conference/workshop papers

{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %} 
  <li>    {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., Brüske, H., and Faber, M. H., "On normalized fatigue crack growth modeling", in Proceedings of the ASME 2020 39th International Conference on Ocean, Offshore and Arctic Engineering (OMAE2020), OMAE2020-18613, 2020 ([link](https://asmedigitalcollection.asme.org/OMAE/proceedings-abstract/OMAE2020/84324/V02AT02A037/1092628)).

* Glavind, S. T., Sepulveda, J. G., Qin, J., and Faber, M. H., "Systems modeling using big data analysis techniques and evidence", in Proceedings of the IEEE 2019 4th International Conference on System Reliability and Safety (ICSRS2019), ICSRS2019-R0119, 2019 ([link](https://ieeexplore.ieee.org/document/8987667)).

* Glavind, S. T., and Faber, M. H., "A framework for offshore load environment modeling", in Proceedings of the ASME 2018 37th International Conference on Ocean, Offshore and Arctic Engineering (OMAE2018), OMAE2018-77674, 2018 ([link](https://asmedigitalcollection.asme.org/OMAE/proceedings-abstract/OMAE2018/51272/V07BT06A006/274135)).

## Theses/reports

{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'thesis' %}
   <li>   {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., "Information-consistent systems modeling and analysis - with applications in offshore engineering", PhD thesis, Aalborg University, expected 2021.

* Glavind, S. T., "Information-consistent systems modeling and analysis - with applications in offshore engineering", MSc thesis, Aarhus University, 2016.
