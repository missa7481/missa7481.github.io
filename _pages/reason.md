---
layout: archive
permalink: /research/reason/
title: "Reason"
author_profile: true
---

<p class="zm-kicker">02 · REASON</p>

<div class="zm-research-intro">Develop grounded and interpretable AI that connects language, geography, knowledge, and system behavior.</div>

## Derivative research projects
<div class="grid__wrapper zm-research-grid">{% assign items = site.research | where:"pillar","reason" | sort:"order_number" %}{% for post in items %}{% include archive-single.html type="grid" %}{% endfor %}</div>
