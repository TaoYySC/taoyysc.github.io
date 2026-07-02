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
* M.S. in Bioinformatics, Tongji University, Shanghai, China, 2024 - Present
  * Zhang Lab, School of Life Sciences and Technology
  * Supervisors: Prof. Menghuan Zhang and Prof. Yong Zhang
  * Research interests: Functional phosphorylation site prediction, deep learning, and protein localization

* B.S. in Computer Science and Technology, Shanghai Ocean University, Shanghai, China, 2020 - 2024
  * Major: Computer Science and Technology
  * School: College of Information Technology


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
