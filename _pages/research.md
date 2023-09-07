---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My primary research thrust revolves around the effective utilization of human-generated data, with a specific
emphasis on harnessing crowdsourced information. My objective is twofold: firstly, to advance our comprehension
of community resilience and to facilitate informed decision-making and management strategies for
natural disasters and unforeseen events. Secondly, to explore citizen awareness of climate change adaptations,
with a vision of contributing to a sustainable future. At the core of my research lies a robust data-driven
framework, encompassing cutting-edge techniques such as machine learning, deep learning, and epidemic
modeling. My research interest extends across several pivotal domains: computational simulations for infrastructure
reliability, AI-enabled risk assessment and monitoring, and transforming education with AI.

My academic research falls into two main areas: understanding the influence of
geography on actor behavior before, during, and after civil conflict, and
developing new tools to improve the study of institutions (both formal and
informal) in peace and conflict. One strand of research in this first area
explores how the territories that ethnic groups inhabit shape rebel group
formation and condition their relationship with the state. My interest in
geography also informs projects on active conflicts including the targeting of
UN peacekeepers by insurgent groups, civilian victimization after rebel
territorial conquest, and communal violence in fragile settings.

My other main research agenda uses advanced methods to develop new measures of
institutions. One project uses Bayesian item response theory to measure the
strength of peace agreements as a latent variable and free researchers from
post-treatment bias caused by using the duration of agreements as a proxy for
their strength. In others, I apply unsupervised learning techniques to over a
billion observations of product-level international trade data to measure
economic interdependence and illicit economic exchange.

In a new avenue of research, I leverage social media data to explore
participation in extremist movements across multiple contexts, gaining insight
into the early stages of radicalization.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
