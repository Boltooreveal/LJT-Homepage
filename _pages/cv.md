---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Education
======

* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–present
* **B.Eng.**, Shanghai Jiao Tong University, 2020–2024; graduated in June 2024

Research Experience
======

* **Research Intern**, MINIMAX, February 2025–present
* **Research Intern**, Tencent WXG, June 2024–September 2024
  * Advisor: Zifei Shan
* **Research Intern**, Shanghai AI Lab, June 2023–December 2023
  * Advisor: Prof. Yu Cheng
* **PhD candidate**, HKUST NLP Group, Hong Kong University of Science and Technology, 2024–present
  * Supervisor: Professor Junxian He

Skills
======

* Natural language processing
* Machine learning
* LLM reasoning and reinforcement learning
* Hallucination in vision-language models
* LLM truthfulness and interpretability

Honors and Awards
======

* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Publications
======

{% for category in site.publication_category %}
<h2>{{ category[1].title }}</h2>
<ul>
  {% for post in site.publications reversed %}
    {% if post.category == category[0] %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>
{% endfor %}

Contact Information
======

* **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* **GitHub:** [Vicent0205](https://github.com/Vicent0205)
* **Google Scholar:** [Junteng Liu's profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* **X:** [@junteng88716710](https://twitter.com/junteng88716710)
