---
layout: archive
title: "Publications[(ResearcherID)](https://orcid.org/0000-0003-1777-0530)"
permalink: /publications/
author_profile: true
---

{% if author.orcid %}
  Publicationss <u><a href="{{author.orcid}}">ORCID profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
