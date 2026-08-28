---
layout: home
title: "Healthcare AI, Machine Learning, and Trustworthy Clinical Systems"
description: "Yashwanth Ramachandra's research-oriented portfolio in Healthcare AI, generative and agentic AI, multimodal learning, and trustworthy clinical systems."
permalink: /
---

<section class="hero">
  <div class="container hero-grid">
    <div>
      <p class="eyebrow">Healthcare AI · Machine Learning · Research</p>
      <h1>Yashwanth<br>Ramachandra</h1>
      <p class="hero-role">Generative &amp; Agentic AI · Multimodal AI · Trustworthy Systems</p>
      <p class="hero-copy">I work at the intersection of artificial intelligence, healthcare, and real-world systems. My interests center on trustworthy multimodal and agentic AI, clinical decision support, generative AI, medical imaging, clinical NLP, and the translation of AI methods into reliable healthcare workflows.</p>
      <div class="button-row">
        <a class="button primary" href="{{ '/research/' | relative_url }}">Explore research direction</a>
        <a class="button secondary" href="{{ '/projects/' | relative_url }}">View projects</a>
      </div>
    </div>
    <aside class="focus-panel" aria-label="Current research direction">
      <p class="eyebrow">Current direction</p>
      <p>Developing the foundation for trustworthy AI systems that can reason across medical imaging, clinical text, structured health data, and medical knowledge to augment clinical decision-making and healthcare workflows.</p>
    </aside>
  </div>
</section>

<section class="section container">
  <div class="section-heading">
    <p class="eyebrow">Research interests</p>
    <h2>Reliable intelligence for complex clinical contexts</h2>
  </div>
  <div class="interest-grid">
    <span>Trustworthy Multimodal AI</span><span>Agentic AI for Healthcare</span>
    <span>Clinical Decision Support</span><span>Generative AI &amp; RAG</span>
    <span>Medical Imaging AI</span><span>Clinical NLP</span>
    <span>Longitudinal Patient Modeling</span><span>Healthcare Informatics</span>
    <span>AI Evaluation &amp; Safety</span><span>Human–AI Collaboration</span>
  </div>
</section>

<section class="section section-tint">
  <div class="container">
    <div class="section-heading split-heading">
      <div><p class="eyebrow">Selected work</p><h2>From components to dependable AI workflows</h2></div>
      <a class="text-link" href="{{ '/projects/' | relative_url }}">All projects →</a>
    </div>
    <div class="project-grid">
      {% for project in site.data.projects limit:3 %}{% include project-card.html project=project %}{% endfor %}
    </div>
  </div>
</section>

<section class="section container two-column">
  <div>
    <p class="eyebrow">Academic goals</p>
    <h2>Applied depth, developed toward rigorous research</h2>
  </div>
  <div>
    <p>I am building toward doctoral research in Computational Precision Health, Biomedical Informatics, Healthcare AI, multimodal learning, and clinical AI agents. The goal is to connect robust methods and careful evaluation with the constraints of real clinical environments.</p>
    <a class="text-link" href="{{ '/about/' | relative_url }}">More about my path →</a>
  </div>
</section>

<section class="section contact-band">
  <div class="container two-column">
    <div><p class="eyebrow">Connect</p><h2>Research, technical exchange, and collaboration</h2></div>
    <div><p>I welcome conversations about trustworthy healthcare AI, research directions, and open technical work.</p><a class="button secondary" href="https://github.com/{{ site.author.github }}">Connect on GitHub</a></div>
  </div>
</section>
