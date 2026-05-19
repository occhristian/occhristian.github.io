---
layout: default
title: Christian Okeke — Portfolio
---

<section class="hero">
  <div class="hero-copy">
    <p class="eyebrow">Developer • Automation Builder • Technical Writer • Tutor</p>
    <h1>I build practical web apps, bots, and automation tools that solve real problems.</h1>
    <p class="lead">I’m Christian Okeke, a Nigeria-based developer focused on Python/Django, React, Node.js, Telegram and WhatsApp bots, crypto tooling, edtech platforms, and clear beginner-friendly technical writing.</p>
    <div class="hero-actions">
      <a class="button primary" href="{{ '/projects/' | relative_url }}">View projects</a>
      <a class="button" href="mailto:{{ site.email }}">Work with me</a>
    </div>
  </div>
  <aside class="hero-card">
    <p class="card-label">Currently focused on</p>
    <h2>EdTech, automation, bots, and full-stack products.</h2>
    <p>I like turning messy workflows into simple dashboards, scripts, bots, and guides people can actually use.</p>
  </aside>
</section>

<section class="section">
  <p class="eyebrow">What I do</p>
  <div class="feature-grid">
    <div class="feature-card"><h3>Full-stack development</h3><p>Django, DRF, React, Node, Prisma, PostgreSQL, dashboards, auth, APIs, and deployment.</p></div>
    <div class="feature-card"><h3>Automation & bots</h3><p>Telegram bots, WhatsApp automations, alerts, background jobs, queue workers, and operational tools.</p></div>
    <div class="feature-card"><h3>Technical education</h3><p>I explain technical ideas in simple language through tutorials, curriculum content, and learner-friendly guides.</p></div>
  </div>
</section>

<section class="section split">
  <div>
    <p class="eyebrow">Selected projects</p>
    <h2>Projects with real-world use cases.</h2>
  </div>
  <a class="text-link" href="{{ '/projects/' | relative_url }}">See all projects →</a>
</section>

<section class="project-grid">
  {% for project in site.data.projects limit: 3 %}
  <article class="project-card">
    <p class="project-type">{{ project.type }}</p>
    <h3>{{ project.name }}</h3>
    <p>{{ project.summary }}</p>
    <p class="stack">{{ project.stack }}</p>
  </article>
  {% endfor %}
</section>

<section class="section split">
  <div>
    <p class="eyebrow">Writing</p>
    <h2>Clear notes from the things I build and debug.</h2>
  </div>
  <a class="text-link" href="{{ '/blog/' | relative_url }}">Read the blog →</a>
</section>

<section class="post-grid">
  {% for post in site.posts limit: 3 %}
  <article class="post-card">
    <p>{{ post.date | date: "%b %-d, %Y" }}</p>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <span>{{ post.categories | join: ', ' }}</span>
  </article>
  {% endfor %}
</section>

<section class="cta">
  <p class="eyebrow">Let’s build</p>
  <h2>Need a developer who can move from idea to working product?</h2>
  <a class="button primary" href="mailto:{{ site.email }}">Send me an email</a>
</section>
