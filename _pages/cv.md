---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **B.Eng. (2020–2024)**, Shanghai Jiao Tong University
* **Ph.D. in Computer Science (2024–Present)**, Hong Kong University of Science and Technology (HKUST)

## Work Experience

* **Research Intern**, MINIMAX (February 2025 – Present)
* **Research Intern**, Tencent WXG (June 2024 – September 2024)
* **Research Intern**, Shanghai AI Lab (June 2023 – December 2023)

## Skills

* Natural Language Processing
* Machine Learning
* LLM reasoning and reinforcement learning
* Hallucination in vision-language models (VLMs)
* LLM truthfulness and interpretability

## Awards

* **Zhiyuan Honor Scholarship**, awarded by Shanghai Jiao Tong University

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
