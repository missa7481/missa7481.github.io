---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

<p class="zm-kicker">RESEARCH AGENDA</p>

<div class="zm-research-intro">My research examines how human-centered AI can understand not only <em>what</em> is happening during a crisis, but <em>where</em>, <em>to whom</em>, and <em>what should happen next</em>. I combine large language models, geospatial analytics, social computing, and systems engineering to model complex human–environment–infrastructure systems.</div>

<div class="zm-method-strip"><span>LLM agents</span><span>Geospatial AI</span><span>Semantic digital twins</span><span>Multimodal learning</span><span>Disaster informatics</span></div>

***

## Professional Services
* **Journal Article Reviewer**
  * <span style="color: green">**Natural Hazard and Risk Management**</span>: International Journal of Disaster Risk Reduction; Natural Hazard Review; Progress in Disaster Science 
  * <span style="color: green">**Urban Planning**</span>: Sustainable Cities and Society; Cities; International Journal of Transportation Science and Technology
  * <span style="color: green">**Artificial Intelligence Technology**</span>: Intelligent Automation & Soft Computing;Computers, Materials & Continua, PeerJ Computer Science 
  * <span style="color: green">**Higher Education**</span>: The Internet and Higher Education
    
* **Conference Proceeding Reviewer**
  * 12NCEE National Conference on Earthquake Engineering

***

## Online Media
* Our research work reported by [Engineering at Maryland](https://eng.umd.edu/disaster-pending)

***

## Research Highlights
<nbsp>

{% include base_path %}
{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}
