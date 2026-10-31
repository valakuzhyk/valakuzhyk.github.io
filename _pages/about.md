---
permalink: /
layout: portfolio
body_class: portfolio-page
title: ""
author_profile: false
excerpt: "Kevin Valakuzhy builds systems for binary analysis, root-cause diagnosis, and LLM-assisted malware analysis."
redirect_from: 
  - /about/
  - /about.html
  - /cv
  - /cv/
  - /resume
  - /resume/
---

<section class="portfolio-intro" aria-labelledby="intro-title">
  <div>
    <p class="portfolio-eyebrow">Security research &amp; systems engineering</p>
    <h1 id="intro-title">Building systems to understand<br class="intro-break"> what software does.</h1>
    <p class="portfolio-bio">I am Kevin Valakuzhy, a PhD candidate at the Georgia Institute of Technology advised by <a href="https://fabianmonrose.github.io/">Fabian Monrose</a>. Before graduate school, I worked as a software engineer at Google and Zeropoint Dynamics. My research focuses on building systems that make binary code analysis more scalable and reliable.</p>
    <div class="portfolio-contact" aria-label="Contact and profiles">
      <a href="mailto:{{ site.author.email }}">Email <span aria-hidden="true">↗</span></a>
      <a href="https://github.com/{{ site.author.github }}">GitHub <span aria-hidden="true">↗</span></a>
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}/">LinkedIn <span aria-hidden="true">↗</span></a>
      <a href="{{ site.author.googlescholar }}">Google Scholar <span aria-hidden="true">↗</span></a>
    </div>
  </div>
  <img class="portfolio-portrait" src="{{ '/images/profile.png' | relative_url }}" alt="Kevin Valakuzhy" width="160" height="160">
</section>

<section class="selected-work" aria-labelledby="selected-work">
  <div class="work-section-heading">
    <h2 id="selected-work">Selected work</h2>
    <p>Execution, evidence, and practical security analysis.</p>
  </div>
  <div class="work-grid">
    {% for project in site.data.projects %}
      {% include project-card.html project=project %}
    {% endfor %}
  </div>
</section>
