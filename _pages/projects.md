---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


## Projects

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
{% endfor %}</ul>