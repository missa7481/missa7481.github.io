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

## Research Highlights

{% include base_path %}
{% assign ordered_pages = site.research | sort:"order_number" %}

<div class="zm-research-accordions">
  <details class="zm-research-accordion">
    <summary>
      <span class="zm-pillar-number">01</span>
      <span class="zm-pillar-copy"><strong>Sense</strong><small>Capture timely human, environmental, and infrastructure signals.</small></span>
      <span class="zm-pillar-action">View projects</span>
    </summary>
    <div class="zm-pillar-projects">
      <div class="grid__wrapper zm-research-grid">{% for post in ordered_pages %}{% if post.pillar == "sense" %}{% include archive-single.html type="grid" %}{% endif %}{% endfor %}</div>
    </div>
  </details>

  <details class="zm-research-accordion">
    <summary>
      <span class="zm-pillar-number">02</span>
      <span class="zm-pillar-copy"><strong>Reason</strong><small>Build grounded, interpretable AI across language, geography, and systems.</small></span>
      <span class="zm-pillar-action">View projects</span>
    </summary>
    <div class="zm-pillar-projects">
      <div class="grid__wrapper zm-research-grid">{% for post in ordered_pages %}{% if post.pillar == "reason" %}{% include archive-single.html type="grid" %}{% endif %}{% endfor %}</div>
    </div>
  </details>

  <details class="zm-research-accordion">
    <summary>
      <span class="zm-pillar-number">03</span>
      <span class="zm-pillar-copy"><strong>Act</strong><small>Turn evidence into equitable planning, risk management, and decisions.</small></span>
      <span class="zm-pillar-action">View projects</span>
    </summary>
    <div class="zm-pillar-projects">
      <div class="grid__wrapper zm-research-grid">{% for post in ordered_pages %}{% if post.pillar == "act" %}{% include archive-single.html type="grid" %}{% endif %}{% endfor %}</div>
    </div>
  </details>
</div>

## Professional Services
* **Journal Article Reviewer**
  * <span style="color: green">**Natural Hazard and Risk Management**</span>: International Journal of Disaster Risk Reduction; Natural Hazard Review; Progress in Disaster Science 
  * <span style="color: green">**Urban Planning**</span>: Sustainable Cities and Society; Cities; International Journal of Transportation Science and Technology
  * <span style="color: green">**Artificial Intelligence Technology**</span>: Intelligent Automation & Soft Computing;Computers, Materials & Continua, PeerJ Computer Science 
  * <span style="color: green">**Higher Education**</span>: The Internet and Higher Education
    
* **Conference Proceeding Reviewer**
  * 12NCEE National Conference on Earthquake Engineering

