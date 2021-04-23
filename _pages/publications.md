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

Papers under review/preprints
---
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
      <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

* Glavind, S. T., Brüske, H., Christensen, E. D, and Faber, M. H., “On systems modeling and context-specific model selection in offshore engineering”, submitted to Computer-Aided Civil and Infrastructure Engineering.

Journal papers
---
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
     <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

Peer reviewed conference/workshop papers
---
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %} 
  <li>    {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

Theses/reports
---
{% comment %}
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'thesis' %}
   <li>   {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>
{% endcomment %}

