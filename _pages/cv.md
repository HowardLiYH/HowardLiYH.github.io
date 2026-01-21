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
* **M.S. in Applied Mathematics and Computational Science**, University of Pennsylvania, 2024-Present
* **B.A. in Mathematics and Economics**, Bowdoin College

Research Interests
======
* Multi-agent systems for financial trading
* Machine learning and deep learning for time-series analysis
* Quantitative methods for operational efficiency and sustainability
* Applied optimization and numerical analysis

Skills
======
* **Programming Languages**: Python, R, MATLAB
* **Machine Learning**: Deep Learning, LLMs, Multi-agent Systems
* **Quantitative Analysis**: Time Series Analysis, Statistical Modeling
* **Financial Applications**: Algorithmic Trading, Risk Management

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Download
======
You can download my full CV as a [PDF](/files/Howard Li_resume_final.pdf).
