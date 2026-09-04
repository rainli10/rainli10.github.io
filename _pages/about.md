---
permalink: /
title: "Rain Li, 李润豪"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am an MSE Robotics student at the University of Pennsylvania and a recent graduate of the Engineering Science program at the University of Toronto, where I specialized in Robotics Engineering. My research broadly lies at the intersection of robot learning, embodied intelligence, and 3D perception.

During my undergraduate studies, I conducted my thesis research on long-horizon vision-language navigation with hierarchical scene-graph memory and agentic reasoning for robustness with Professor Professor [Steven Waslander](https://www.trailab.utias.utoronto.ca/steven-waslander) in [Toronto Robotics and AI Lab (TRAIL)](https://www.trailab.utias.utoronto.ca/). Previously, I worked as student researcher at [Robot Vision & Learning (RVL) lab](https://rvl.cs.toronto.edu/) with Professor [Florian Shkurti](https://www.cs.toronto.edu/~florian/) on Sparse-view 4D Gaussian Splatting. I also completed a 12-month co-op as Researcher at [Noah's Ark Lab Canada](http://dev3.noahlab.com.hk/) on Autonomous Driving team, focusing 3D reconstruction and generative AI on 3D. In addition, I had multiple summer internships at [SenseTime Inc](https://www.sensetime.com/en) where I worked on NeRF and benchmarking Autonomous Driving algorithms.




## Research Interests

My long-term research goal is to develop intelligent robotic systems that can perceive, reason, learn, and act effectively in complex real-world environments.

I am particularly interested in:

- **Robot Learning & Embodied AI:** generalizable robot policies, vision-language-action models, imitation learning, reinforcement learning, and adaptive robot behavior.
- **3D/4D Perception:** developing generalizable methods for 3D and 4D scene understanding, generative models, reconstruction, and perception in complex real-world environments.

My current goal is to increasingly connect my previous work in embodied perception, navigation, and 3D scene understanding with learning-based robotic decision-making and control.



Research Experiences
======

{% include base_path %}

{%- if site.publication_category -%}
{%- for category in site.publication_category -%}
{%- assign title_shown = false -%}
{%- for post in site.publications reversed -%}
{%- if post.category != category[0] -%}
{%- continue -%}
{%- endif -%}
{%- unless title_shown -%}
<h2>{{ category[1].title }}</h2><hr />
{%- assign title_shown = true -%}
{%- endunless -%}
{%- include archive-single.html -%}
{%- endfor -%}
{%- endfor -%}
{%- else -%}
{%- for post in site.publications reversed -%}
{%- include archive-single.html -%}
{%- endfor -%}
{%- endif -%}
