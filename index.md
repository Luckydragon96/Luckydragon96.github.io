---
layout: default
title: Home
---

<section class="hero">
  <div class="hero__portrait">
    <img src="{{ '/assets/img/profile.png' | relative_url }}" alt="Portrait of Xiaolong Li">
  </div>
  <div class="hero__content">
    <p class="eyebrow">{{ site.author.role }}</p>
    <h1>{{ site.author.name }}</h1>
    <p class="lead">
      I am a postdoctoral researcher at the School of Economics and Management,
      Dalian University of Technology. I received my Ph.D. in Control Science and
      Engineering from Northeastern University in Shenyang, China.
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
    and data-driven decision support for complex operational systems. I am especially
    interested in problems where rigorous optimization methods meet practical
    industrial constraints.
  </p>
</section>

<section class="section section--grid">
  <article>
    <p class="eyebrow">Selected Work</p>
    <h2>Recent Publications</h2>
    <ul class="item-list">
      <li>
        <div class="publication-heading"><strong class="publication-title">An exact branch-price-and-cut algorithm for the unrelated parallel machine scheduling problem.</strong> <span class="pub-badges"><span class="pub-badge">同等贡献</span><span class="pub-badge">通讯作者</span><span class="pub-badge">UTD 24</span></span></div>
        <span>Yu, Yang; <strong>Li, Xiaolong</strong>; Baldacci, Roberto; Wu, Zhiqiao; Sun, Wei; Tang, Jiafu; Zhu, Han. <em>INFORMS Journal on Computing</em>, 2026.</span>
      </li>
      <li>
        <div class="publication-heading"><strong class="publication-title">Evolve-learn-adjust for seru production system.</strong> <span class="pub-badges"><span class="pub-badge">同等贡献</span><span class="pub-badge">通讯作者</span><span class="pub-badge">ABS 3</span></span></div>
        <span>Zhang, Zhecong; Yu, Yang; <strong>Li, Xiaolong</strong>; Huang, Yutong; Wu, Zhiqiao; Meng, Runshi. <em>International Journal of Production Research</em>, 2026.</span>
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
