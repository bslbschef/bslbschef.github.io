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
I am currently a second-year master student at GTIIT, supervised by Prof. [Cheng Li](https://sites.gtiit.edu.cn/cligroup/), with Prof. Zvi Pinhas Bar-Yoseph serving as my co-supervisor at Technion. I completed my B.E. degree in Automation at Central South University.

## Research interests
My research primarily centers on fluid dynamics and intelligent measurement technologies, emphasizing experimental and computational methods.

Previously, I conducted research on particle segregation phenomena in fluidized beds, where I developed a non-intrusive characterization approach combining image segmentation techniques with deep learning (VGG19 classifier). This method effectively addresses challenges associated with invasive measurement techniques and has been published in Chemical Engineering Journal. Additionally, I contributed to designing and developing a UAV-based integrated measurement platform capable of simultaneous wind speed and particle data collection at altitudes up to 1000 meters, published in Experiments in Fluids and presented at the APS Conference in 2023.

Currently, my ongoing research includes:

1. Implementing a deep generative diffusion model aimed at correcting UAV-derived wind speed measurements, with preliminary outcomes leading to a patent application.
2. Employing Physics-Informed Neural Networks (PINN) for reconstructing wind fields from sparse UAV observations, validated through field experiments.

For doctoral studies, I plan to extend my research into robotics, focusing on bio-inspired robots such as flapping-wing drones and humanoid robots. My objective is to incorporate physics-informed reinforcement learning techniques to enhance robotic control, efficiency, and autonomy in complex environments.

## Publications
<ul>{% for post in site.publications reversed %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
