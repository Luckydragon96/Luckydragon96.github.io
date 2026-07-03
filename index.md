---
layout: default
title: Home
---

<section class="hero">
  <div class="hero__portrait">
    <img src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Profile portrait placeholder">
  </div>
  <div class="hero__content">
    <p class="eyebrow">{{ site.author.role }}</p>
    <h1>{{ site.author.name }}</h1>
    <p class="lead">
      I am a researcher at {{ site.author.affiliation }} working on optimization, analytics,
      and decision-making methods for complex operational systems.
    </p>
    <div class="hero__actions">
      <a class="button button--primary" href="{{ '/cv/' | relative_url }}">View CV</a>
      <a class="button" href="mailto:{{ site.author.email }}">Contact</a>
    </div>
  </div>
</section>

<section class="section">
  <div class="section__heading">
    <p class="eyebrow">Research</p>
    <h2>Research Interests</h2>
  </div>
  <div class="tag-list">
    {% for interest in site.research_interests %}
      <span>{{ interest }}</span>
    {% endfor %}
  </div>
  <p>
    My current work focuses on mathematical modeling, exact and heuristic algorithms,
    and data-driven decision support. I am especially interested in problems where
    rigorous optimization methods meet practical industrial constraints.
  </p>
</section>

<section class="section section--grid">
  <article>
    <p class="eyebrow">Selected Work</p>
    <h2>Recent Publications</h2>
    <ul class="item-list">
      <li>
        <strong>Paper Title on Optimization and Decision Analytics.</strong>
        <span>Your Name, Coauthor Name. Journal or Conference, 2026.</span>
      </li>
      <li>
        <strong>Learning-Enhanced Algorithms for Complex Scheduling Problems.</strong>
        <span>Your Name, Coauthor Name. Working paper.</span>
      </li>
    </ul>
    <a class="text-link" href="{{ '/publications/' | relative_url }}">All publications</a>
  </article>

  <article>
    <p class="eyebrow">Updates</p>
    <h2>News</h2>
    <ul class="timeline">
      <li>
        <time>2026</time>
        <span>Started a new research project on optimization and intelligent decision systems.</span>
      </li>
      <li>
        <time>2025</time>
        <span>Presented recent work at an international operations research conference.</span>
      </li>
    </ul>
  </article>
</section>
