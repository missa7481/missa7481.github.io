---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My primary research thrust revolves around effectively utilizing **human-generated data**, specifically harnessing crowdsourced information. My objective is twofold: <span style="color: green"> firstly</span>, to advance our comprehension of community resilience and to facilitate informed decision-making and management strategies for natural disasters and unforeseen events. <span style="color: green"> Secondly </span>, to explore the nexus of humans, infrastructure, and climate change in urban environments, with a vision of contributing to a sustainable future. At the core of my research lies robust and data-driven frameworks encompassing cutting-edge techniques such as machine learning, deep learning, network analysis, and epidemic modeling. My research interest extends across several pivotal domains: computational simulations for infrastructure reliability, AI-enabled risk assessment and monitoring, and transforming education with AI.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
