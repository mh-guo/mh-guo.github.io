---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV here](https://mh-guo.github.io/CV_Minghao_Guo.pdf)
=====

Education
======
* Ph.D student in Astrophysics, Princeton University, 2026 (expected)
* M.S. in Astrophysics, Princeton University, 2023
* B.S. in Physics, Peking University, 2021

Experience
======
* Visiting graduate student at the Institute for Advanced Study, Dec 2023 -- 2026 (expected)

Research
======
  1. Black hole accretion and feedback, Active galactic nuclei (AGN)
  1. Multiphase interstellar medium (ISM), supernova remnant
  1. Numerical methods and simulations, GPU computing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Service and leadership
======
* Teaching Astronomy in Prison Teaching Initiative
* Member of the Learning the Universe Collaboration
* Reviewer for the Astrophysical Journal (ApJ)
* Astronomy on Tap Trenton Talk
* Co-advising Princeton Undergraduate: Sajia Shahrin Neha, Milo Salvucci

Skills
======
* Massive parallel computing on supercomputer
  * massive parallel computing
  * dataset analyzing
  * visualization

Software development
======
* [AhtenaK](https://github.com/IAS-Astrophysics/athenak) (Developer): Block-based AMR framework with fluid, particle and numerical relativity solvers in Kokkos.
* [AthenaKit](https://github.com/mh-guo/athenakit) (Owner): Toolkit for data analyzing and visualization with AthenaK
* [pySTGROMX](https://github.com/mh-guo/pySTGROMX) (Owner): Extended reduced-order surrogate models for scalar-tensor gravity of Damour and Esposito-Farèse (DEF)

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>  
