---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Coloured Petri Net Plans for Cooperative Multi-robot Systems
Lorenzo Steccanella, Alessandro Farinelli, Luca Iocchi, Daniele Nardi. Coloured Petri Net
Plans for Cooperative Multi-robot Systems - In Proceedings of the 3rd Italian Workshop on
Artificial Intelligence and Robotics (AIRO) Genova, 28 November, 2016.

* Waterline and obstacle detection in images from low-cost autonomous boats
Steccanella Lorenzo, et al. Waterline and obstacle detection in images from low-cost autono-
mous boats for environmental monitoring. - Robotics and Autonomous Systems 124 (2020):
103346.

* Hierarchical reinforcement learning for efficient exploration and transfer
Steccanella Lorenzo, et al. Hierarchical reinforcement learning for efficient exploration and
transfer. - 4th Lifelong Learning Workshop at ICML 2020.

* Hierarchical Representation Learning for Markov Decision Processes
Steccanella Lorenzo, et al. Hierarchical Representation Learning for Markov Decision Pro-
cesses. - IJCAI 2021 Generalization in Planning Workshop.

* State Representation Learning for Goal-Conditioned Reinforcement Learning
Steccanella Lorenzo, et al. State Representation Learning for Goal-Conditioned Reinforce-
ment Learning - arXiv preprint arXiv:2205.01965 (2022)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
