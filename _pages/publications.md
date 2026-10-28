---
layout: page
title: Publications
permalink: /publications
---
{% for item in site.data.publications %}
  {% include publication-item.html %}
{% endfor %}
