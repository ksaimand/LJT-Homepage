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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024 (expected 2029)
* B.Eng., Shanghai Jiao Tong University, 2024

Work experience
======
* February 2025 - Present: Research Intern
  * MINIMAX
  * Research on natural language processing and machine learning

* June 2024 - September 2024: Research Intern
  * Tencent WXG
  * Advisor: Zifei Shan
  * Research on natural language processing

* June 2023 - December 2023: Research Intern
  * Shanghai AI Lab
  * Advisor: Prof. Yu Cheng
  * Research on natural language processing

Skills
======
* Programming Languages: Python, C++, JavaScript, HTML/CSS
* Machine Learning / NLP: PyTorch, TensorFlow, Hugging Face Transformers, NLP, LLM
* Tools / Platforms: Git, Linux, Docker, Jupyter

Publications
======
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
Talks
======
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}
  
Teaching
======
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
Awards and Honors
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University
