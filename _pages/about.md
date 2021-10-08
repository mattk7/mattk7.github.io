---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me
---

I am a Senior Research Scientist at the Laboratory for the Modeling of Biological and Socio-Technical Systems (MOBS Lab) and my work focuses primarily on developing large-scale, data-driven computational models to study and forecast the spatial spread of infectious diseases while considering the impact of changes in human behavior (e.g. mobility, contact patterns, vaccine hesitancy, ..) and policy interventions. 

My research interests include: a) the development of computational and analytical models to study and forecast the spatial spread of infectious diseases; b) the development of agent-based models to create realistic representations of population dynamics; c) the study of human mobility and contact patterns using high-resolution large-scale de-identified location data; d) combining mechanistic epidemic models with machine learning/deep learning frameworks; and e) the study of the evolution and structure of science and innovation.

<center>
<video width='100%' autoplay playsinline loop>
  <source src="/images/sir_new.webm" type="video/webm">
  <source src="/images/sir_new.m4v" type="video/mp4">

  Your browser does not support the video tag.
</video>
</center>

<br>
<br>
<br>


# Current projects
---

{% for post in site.current_projects %}
  {% include archive-single.html %}
{% endfor %}

