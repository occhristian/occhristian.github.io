---
title: Projects
icon: fas fa-code
order: 2
---

# Projects

Here are some of the product areas and real-world builds I have worked on.

{% for project in site.data.projects %}
## {{ project.name }}

**Type:** {{ project.type }}  
**Stack:** {{ project.stack }}

{{ project.summary }}

**Impact:** {{ project.impact }}

---
{% endfor %}
