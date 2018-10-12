---
layout: archive
title: "Publications"
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
