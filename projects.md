---
layout: page
title: Projects
description: A focused list of projects and product areas I have worked on.
permalink: /projects/
---

<div class="project-list">
{% for project in site.data.projects %}
<article class="project-card wide">
  <p class="project-type">{{ project.type }}</p>
  <h2>{{ project.name }}</h2>
  <p>{{ project.summary }}</p>
  <p><strong>Impact:</strong> {{ project.impact }}</p>
  <p class="stack">{{ project.stack }}</p>
  {% for link in project.links %}<a class="text-link" href="{{ link.url }}">{{ link.label }} →</a>{% endfor %}
</article>
{% endfor %}
</div>
