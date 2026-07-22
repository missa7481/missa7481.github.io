---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<div class="zm-focus-grid zm-pillar-links">
  <a href="/research/sense/"><span>01</span><h3>Sense</h3><p>Work that extracts human, environmental, and infrastructure signals.</p></a>
  <a href="/research/reason/"><span>02</span><h3>Reason</h3><p>Work advancing AI reasoning, language models, and system representations.</p></a>
  <a href="/research/act/"><span>03</span><h3>Act</h3><p>Work translating evidence into planning, response, and management.</p></a>
</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship
