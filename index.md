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
    My research focuses on combinatorial optimization problems in production and
    scheduling, including unrelated parallel machine scheduling and operational
    optimization for seru production systems. I am particularly interested in the
    design of exact algorithms such as branch-price-and-cut and Benders
    decomposition, artificial intelligence algorithms such as graph neural networks
    and deep reinforcement learning, AI-driven exact optimization, and large-scale
    exact-solution-guided deep reinforcement learning.
  </p>
</section>

<section class="section section--grid">
  <article>
    <p class="eyebrow">Selected Work</p>
    <h2>Recent Publications</h2>
    <ul class="item-list">
      <li>
        <div class="publication-heading"><strong class="publication-title">An exact branch-price-and-cut algorithm for the unrelated parallel machine scheduling problem.</strong> <span class="pub-badges"><span class="pub-badge pub-badge--role">Equal Contribution</span><span class="pub-badge pub-badge--role">Corresponding Author</span><span class="pub-badge pub-badge--utd">UTD 24</span></span></div>
        <span>Yu, Yang; <strong>Li, Xiaolong</strong>; Baldacci, Roberto; Wu, Zhiqiao; Sun, Wei; Tang, Jiafu; Zhu, Han. <em>INFORMS Journal on Computing</em>, 2026. <a class="doi-link" href="https://doi.org/10.1287/ijoc.2024.0704">DOI</a></span>
      </li>
      <li>
        <div class="publication-heading"><strong class="publication-title">Evolve-learn-adjust for seru production system.</strong> <span class="pub-badges"><span class="pub-badge pub-badge--role">Equal Contribution</span><span class="pub-badge pub-badge--role">Corresponding Author</span><span class="pub-badge pub-badge--abs">ABS 3</span></span></div>
        <span>Zhang, Zhecong; Yu, Yang; <strong>Li, Xiaolong</strong>; Huang, Yutong; Wu, Zhiqiao; Meng, Runshi. <em>International Journal of Production Research</em>, 2026. <a class="doi-link" href="https://doi.org/10.1080/00207543.2026.2633591">DOI</a></span>
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
        <span>Our paper on exact branch-price-and-cut algorithms for unrelated parallel machine scheduling appeared in <em>INFORMS Journal on Computing</em>.</span>
      </li>
      <li>
        <time>2026</time>
        <span>Our paper on evolve-learn-adjust methods for seru production systems appeared in <em>International Journal of Production Research</em>.</span>
      </li>
      <li>
        <time>2025.07</time>
        <span>Joined the School of Economics and Management, Dalian University of Technology, as a postdoctoral researcher.</span>
      </li>
      <li>
        <time>2025.06</time>
        <span>Received the Ph.D. degree in Control Science and Engineering from Northeastern University.</span>
      </li>
      <li>
        <time>2025</time>
        <span>Our paper on a hypervolume-based Q-learning cooperative co-evolution algorithm for hybrid seru systems appeared in <em>European Journal of Operational Research</em>.</span>
      </li>
    </ul>
  </article>
</section>
