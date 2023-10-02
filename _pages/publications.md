---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
## Publications
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Research Projects
---

### Metalens-based Optical Multiparameter Detection
_Supervisor_ : Prof. [Zhenyu Yang](http://nanophotonics.oei.hust.edu.cn/info/1101/1183.htm) 
_September 2022 – January 2023_

- **Description:** In this project, I designed metalens to reconstruct the Stokes parametrization of light based on PB phase modulation, Hartmann-shack wavefront detection principle. The incident light intensity was detected by 4~6 different polarization-sensitive lenses to reconstruct the Stokes parameter of the incident light.
  
- **Tools:** Lumerical FDTD solutions, MATLAB, Python

- **Accomplishments:** Completed a research presentation. You can view the report in Chinese [here](https://jinyan-sivan.github.io/files/report.pdf).

### Drug-Interaction Prediction based on Chain-of-Thought Prompting in GPT3.5
_Supervisor_ : Prof. [Pengtao Xie](https://pengtaoxie.github.io/)
_June 2023 - October 2023_

- **Description:** In this project, I designed a series of logical steps named Chain-of-Thought (CoT) for the GPT intended for drug-drug interaction (DDI) prediction. By fine-tuning GPT3.5, I increased the accuracy of GPT's prediction on DDIs.

- **Tools:** Python

- **Accomplishments:** I am trying to finish a paper. You can see the ongoing project [here](https://www.overleaf.com/read/jkmygbwkmrvc).

### Metalens-based rotating zoom lens set
_Supervisor_ : Prof. [Zhenyu Yang](http://nanophotonics.oei.hust.edu.cn/info/1101/1183.htm) 
_March 2023 – now_

- **Description:** In this project, I explored the rotation zoom rule of a single metalens array: $$ F(\theta) = \frac{\pi}{\theta} \times F_0 $$, where $$ F(\theta) $$ is the array's EFFL, $$ F_0 $$ is the minimum focal length, and $$ \theta $$ is the rotation angle. Then I designed a 3-lens optical system whose BFL is a fixed number.

- **Tools:** Lumerical FDTD solutions, MATLAB

- **Accomplishments:** Still preparing the manuscript.
