---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
---

## Job Market Paper

{% include base_path %}

{% for post in site.jmp reversed %}
{% include archive-single.html %}
{% endfor %}

## Working Papers

{% include base_path %}

{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
