---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My primary research thrust revolves around effectively utilizing **human-generated data**, specifically harnessing crowdsourced information. My objective is twofold: <span style="color: green"> firstly</span>, to advance our comprehension of community resilience and to facilitate informed decision-making and management strategies for natural disasters and unforeseen events. <span style="color: green"> Secondly</span>, to explore the nexus of humans, infrastructure, and climate change in urban environments, with a vision of contributing to a sustainable future. At the core of my research lies robust and data-driven frameworks encompassing cutting-edge techniques such as machine learning, deep learning, network analysis, and epidemic modeling. My research interest extends across several pivotal domains: computational simulations for infrastructure reliability, AI-enabled risk assessment and monitoring, and transforming education with AI.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

Reviews
======
* **Journal Article Reviewer**
  * <span style="color: green">**Natural Hazard and Risk Management**</span>: International Journal of Disaster Risk Reduction; Natural Hazard Review
  * <span style="color: green">**Urban Planning**</span>: Sustainable Cities and Society; Cities; International Journal of Transportation Science and Technology
  * <span style="color: green">**Artificial Intelligence Technology**</span>: Intelligent Automation & Soft Computing;Computers, Materials & Continua
  * <span style="color: green">**Higher Education**</span>: The Internet and Higher Education
    
* **Conference Proceeding Reviewer**
  * 12NCEE National Conference on Earthquake Engineering
    
Online Media
======
* Our research work reported by [Engineering at Maryland](https://eng.umd.edu/disaster-pending)
