---
layout: archive
permalink: /research/sense/
title: "Sense"
author_profile: true
---

<p class="zm-kicker">01 · SENSE</p>

<div class="zm-research-intro">Capture timely human, environmental, and infrastructure signals so complex events can be observed across people, places, and systems.</div>

## Research projects
<div class="grid__wrapper zm-research-grid">{% assign items = site.research | where:"pillar","sense" | sort:"order_number" %}{% for post in items %}{% include archive-single.html type="grid" %}{% endfor %}</div>

## Related publications
{% assign papers = site.publications | where:"pillar","sense" | sort:"date" | reverse %}{% for post in papers %}{% include archive-single.html %}{% endfor %}
