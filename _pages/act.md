---
layout: archive
permalink: /research/act/
title: "Act"
author_profile: true
---

<p class="zm-kicker">03 · ACT</p>

<div class="zm-research-intro">Translate evidence into situational awareness, equitable planning, risk management, and adaptive decisions.</div>

## Research projects
<div class="grid__wrapper zm-research-grid">{% assign items = site.research | where:"pillar","act" | sort:"order_number" %}{% for post in items %}{% include archive-single.html type="grid" %}{% endfor %}</div>

## Related publications
{% assign papers = site.publications | where:"pillar","act" | sort:"date" | reverse %}{% for post in papers %}{% include archive-single.html %}{% endfor %}
