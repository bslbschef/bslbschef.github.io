---
permalink: /
layout: archive
title: "Biaosheng Luo Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /aboutme
  - /_pages/about
---

## About me
<!-- I am currently a second-year master student at GTIIT, supervised by Prof. [Cheng Li](https://sites.gtiit.edu.cn/cligroup/), with Prof. Zvi Pinhas Bar-Yoseph serving as my co-supervisor at Technion. I completed my B.E. degree in Automation at Central South University. -->

I am currently a second-year master's student in Mechanical Engineering at the Technion–Israel Institute of Technology, enrolled in a joint training program with GTIIT. My primary advisor is Prof. [Cheng Li](https://sites.gtiit.edu.cn/cligroup/) at GTIIT, and I am co-supervised by Prof. [Zvi Pinhas Bar-Yoseph](https://meeng.technion.ac.il/en/member/zvi-pinhas-bar-yoseph/) at Technion. I completed my B.E. degree in Automation at Central South University.

<!-- My research focuses on developing UAV-based platforms for simultaneous wind and particle measurements in the atmospheric boundary layer. -->

## Research interests

My research interests span bio-inspired robotics, particularly focusing on bipedal robots, flapping-wing drones, and humanoid robots. I'm committed to integrating physics-informed machine learning and reinforcement learning techniques to enhance robotic locomotion, control efficiency, and autonomy, especially in complex and dynamic environments. 

Additionally, I have experience with fluid dynamics and intelligent measurement technologies, combining experimental and computational approaches. Currently, I am actively seeking PhD opportunities to further explore and expand these interdisciplinary research directions.


## Publications
<ul>{% for post in site.publications reversed %}
{% include archive-single-cv.html %}
{% endfor %}</ul>


<!-- ## Projects

### ● Robotics and Embodied AI
<ul>{% for post in site.projects reversed %}
{% assign filename = post.path | split: "/" | last | split: "." | first %}
{% if filename contains "Robot" or filename contains "LLM" %}
{% include archive-single-cv-project.html %}
{% endif %}
{% endfor %}</ul>

### ● UAV-Based Sensing and Control
<ul>{% for post in site.projects reversed %}
{% assign filename = post.path | split: "/" | last | split: "." | first %}
{% if filename contains "UAV" %}
{% include archive-single-cv-project.html %}
{% endif %}
{% endfor %}</ul>

### ● Imaging and Flow Characterization 
<ul>{% for post in site.projects reversed %}
{% assign filename = post.path | split: "/" | last | split: "." | first %}
{% if filename contains "CycleGAN" or filename contains "DIH" %}
{% include archive-single-cv-project.html %}
{% endif %}
{% endfor %}</ul> -->