---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My academic research falls into two main areas: the development of Reduced Order Models (ROM) for multi-physics systems, involving the integration of experimental data with mathematical models, and the investigation of techniques able to reconstruct complex fields from the measure of other variables, easier to be detected.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
