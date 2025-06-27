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
<!-- My research primarily centers on fluid dynamics and intelligent measurement technologies, emphasizing experimental and computational methods. 

Previously, I conducted research on particle segregation phenomena in fluidized beds, where I developed a non-intrusive characterization approach combining image segmentation techniques with deep learning (VGG19 classifier). This method effectively addresses challenges associated with invasive measurement techniques and has been published in Chemical Engineering Journal. Additionally, I contributed to designing and developing a UAV-based integrated measurement platform capable of simultaneous wind speed and particle data collection at altitudes up to 1000 meters, published in Experiments in Fluids and presented at the APS Conference in 2023.

Currently, my ongoing research includes:

1. Implementing a deep generative diffusion model aimed at correcting UAV-derived wind speed measurements, with preliminary outcomes leading to a patent application.
2. Employing Physics-Informed Neural Networks (PINN) for reconstructing wind fields from sparse UAV observations, validated through field experiments.

For doctoral studies, I plan to extend my research into robotics, focusing on bio-inspired robots such as flapping-wing drones and humanoid robots. My objective is to incorporate physics-informed reinforcement learning techniques to enhance robotic control, efficiency, and autonomy in complex environments. -->
My research primarily centers on fluid dynamics and intelligent measurement technologies, emphasizing experimental and computational methods.

<!-- <u>Currently, I'm actively seeking PhD opportunities.</u> For doctoral studies, I am interested in expanding my research into multiple exciting directions, including bio-inspired robotics (such as flapping-wing drones, humanoid robots, and bipedal robots), large language models and AI applications, as well as the intersection of physics-informed machine learning with autonomous systems. My research interests encompass leveraging advanced computational techniques—including reinforcement learning, neural networks, and large-scale models—to enhance robotic control, improve system intelligence, and advance autonomous capabilities across diverse and challenging environments.  -->

<u>Currently, I'm actively seeking PhD opportunities.</u> For doctoral studies, I plan to extend my research into robotics, focusing on bio-inspired robots such as flapping-wing drones and humanoid robots. My objective is to incorporate physics-informed reinforcement learning techniques to enhance robotic control, efficiency, and autonomy in complex environments.

<!-- <u>I am currently seeking PhD positions</u> and welcome opportunities in any of the following areas, each of which could form the basis of my doctoral research:

- **Bio-inspired robotics** (e.g. flapping-wing drones, humanoid and bipedal robots)  
- **Large language models & AI applications**  
- **Physics-informed machine learning for autonomous systems**  

My goal is to leverage advanced computational methods—reinforcement learning, deep neural networks, and large-scale modeling—to push the frontiers of robotic control and autonomy. I would be delighted to collaborate with a professor working in any of these fields.   -->


## Publications
<ul>{% for post in site.publications reversed %}
{% include archive-single-cv.html %}
{% endfor %}</ul>


## Selected Projects

### 🧠 Robotics and Embodied AI
<ul>{% for post in site.projects reversed %}
{% assign filename = post.path | split: "/" | last | split: "." | first %}
{% if filename contains "Robot" or filename contains "LLM" %}
{% include archive-single-cv-project.html %}
{% endif %}
{% endfor %}</ul>

### 🌪️ UAV-Based Sensing and Control
<ul>{% for post in site.projects reversed %}
{% assign filename = post.path | split: "/" | last | split: "." | first %}
{% if filename contains "UAV" %}
{% include archive-single-cv-project.html %}
{% endif %}
{% endfor %}</ul>

### 📷 Imaging and Flow Characterization 
<ul>{% for post in site.projects reversed %}
{% assign filename = post.path | split: "/" | last | split: "." | first %}
{% if filename contains "CycleGAN" or filename contains "DIH" %}
{% include archive-single-cv-project.html %}
{% endif %}
{% endfor %}</ul>