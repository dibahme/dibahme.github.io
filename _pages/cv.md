---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 2023-Present: Ph.D. in Computer Science, EPFL, Lausanne, Switzerland
  * Machine Learning and Optimization Lab (MLO), Supervisor: Martin Jaggi
  * Expected graduation: 2027

Research experience
======
* 2026-Present: Research Scientist Intern, Pretraining Team, Mistral AI, Paris, France

Internships and summer schools
======
* Summer 2022: Internship on Streaming Algorithms, EPFL
  * Supervisor: Ola Svensson
* 2022: Summer School in Modern Trends in Combinatorial Optimization, Bernoulli Center, EPFL
* 2021: Internship on Distributed Algorithms and Machine Learning, IST Austria
  * Supervisor: Dan Alistarh

Skills
======
* Programming: Python, C/C++, Java
* ML & Deep Learning: PyTorch, NumPy, Pandas; large-scale distributed training (FSDP, tensor / expert / context parallelism)
* GPU & Systems: custom GPU kernels (Triton, TileLang, CUDA), SLURM, multi-node GPU clusters
* Tools: Git, LaTeX, Hugging Face, Weights & Biases
* Languages: English (fluent), French (B1, intermediate)

Honors and Awards
======
* 2021: 2nd place, 1st National [Optimizer!](https://github.com/mtefagh/Optimizer) Competition, a contest on problems in convex optimization
* 2019: National Universities Entrance Exam, ranked 343rd among 160,000+ participants
* 2018: Silver Medal, National Olympiad in Informatics (top 40 nationally)
* 2018: 1st place, CodeCup National Programming Competition

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
