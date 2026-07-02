---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/Tengrui_CV.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>

Education
======
* Ph.D. in Computer Science, Missouri University of Science and Technology, 2030 (expected), advised by [Dr. Park](https://sites.mst.edu/sjpark/)
* M.S. in Computer Science, Missouri University of Science and Technology, May 2026
* M.S. in Finance, University of International Business and Economics, 2015
* B.S. in Communication Engineering, East China Jiaotong University, 2012

Experience
======
* Ph.D./M.S. Research — Missouri University of Science and Technology
  * Working on trustworthy, reliable machine learning for biomedical and scientific applications
  * First-author research on functional connectivity diagnosis (BrainLRR)
  * Co-authored SciTables, a table-to-text generation dataset and benchmark accepted to VLDB 2026

Professional Experience
======
* Nov 2020 - Jun 2024: Principal Research Staff Member (Data Analytic)
  * Changsha Science and Technology Bureau, Changsha, Hunan, China

* Oct 2019 - Nov 2020: Bond Investment Analyst, Fixed Income Department
  * First State Cinda Fund Management Co., Ltd.

* Jun 2015 - Oct 2019: Bond Investment Analyst, Fixed Income Department
  * Yingda Securities Co., Ltd.

Skills
======
* Python, PyTorch, Hugging Face
* NLP, LLMs, LaTeX parsing
* Graph-based deep learning, foundation model evaluation

Publications
======
  <ul>{% assign sorted_publications = site.publications | sort: 'date' | reverse %}{% for post in sorted_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% if site.talks.size > 0 %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% endif %}

{% if site.teaching.size > 0 %}
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}

Service and leadership
======
* Active contributor to the international student community at Missouri S&T, supporting peer mentoring and cross-cultural initiatives
