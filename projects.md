---
title: "Projects"
eyebrow: "Selected technical work"
description: "Research-oriented AI projects documented by problem, method, evaluation, limitations, and next steps."
permalink: /projects/
---

The portfolio currently contains one documented research exploration. Additional work will be added only when its scope, evidence, and evaluation can be described accurately.

<div class="project-grid page-grid">
{% for project in site.data.projects %}{% include project-card.html project=project %}{% endfor %}
</div>

## Evaluation standard

Project pages distinguish implemented work from planned work. When quantitative results are not yet available, that absence is stated directly rather than replaced with estimated or illustrative metrics.
