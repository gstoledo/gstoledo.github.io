---
title: "Research"
permalink: /research/
author_profile: true
---
Recent Working papers:

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}