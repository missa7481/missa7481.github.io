---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="zm-publication-intro">Selected work at the intersection of large language models, agentic AI, geospatial intelligence, digital twins, and human-centered disaster systems.</div>

{% include base_path %}

## Selected AI Conference Publications

<p class="zm-section-note">Accepted work at leading international venues in artificial intelligence and natural language processing.</p>

{% assign ai_conferences = site.publications | where:"pub_type","ai_conference" | where:"conference_status","accepted" | sort:"date" | reverse %}
<div class="zm-ai-pub-grid">
{% for post in ai_conferences %}
  <article class="zm-ai-pub-card">
    <div class="zm-ai-pub-meta"><span>{{ post.venue_short }}</span><time>{{ post.date | date: "%Y" }}</time></div>
    <h3><a href="{{ post.link }}">{{ post.title }}</a></h3>
    <p>{{ post.card_summary }}</p>
    {% if post.ai_topics %}<div class="zm-ai-topics">{% for topic in post.ai_topics %}<span>{{ topic }}</span>{% endfor %}</div>{% endif %}
    <a class="zm-ai-paper-link" href="{{ post.link }}">View publication →</a>
  </article>
{% endfor %}
</div>

### AI Conference Submission

{% assign ai_submissions = site.publications | where:"pub_type","ai_conference" | where:"conference_status","under_review" | sort:"date" | reverse %}
<div class="zm-ai-pub-grid zm-ai-submissions">
{% for post in ai_submissions %}
  <article class="zm-ai-pub-card is-submission">
    <div class="zm-ai-pub-meta"><span>{{ post.venue_short }} · UNDER REVIEW</span><time>{{ post.date | date: "%Y" }}</time></div>
    <h3><a href="{{ post.link }}">{{ post.title }}</a></h3>
    <p>{{ post.card_summary }}</p>
    {% if post.ai_topics %}<div class="zm-ai-topics">{% for topic in post.ai_topics %}<span>{{ topic }}</span>{% endfor %}</div>{% endif %}
    <a class="zm-ai-paper-link" href="{{ post.link }}">View preprint →</a>
  </article>
{% endfor %}
</div>

## Peer-Reviewed Journal Articles

{% assign journals = site.publications | where:"pub_type","journal" | sort:"date" | reverse %}
{% for post in journals %}{% include archive-single.html %}{% endfor %}

{% if author.googlescholar %}
  View the complete record on <u><a href="{{author.googlescholar}}">Google Scholar</a></u>.
{% endif %}

<sup>*</sup> Equal authorship
