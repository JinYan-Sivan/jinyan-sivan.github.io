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
  
- **Tools:** Lumerical FDTD solutions, MATLAB, Python.

- **Accomplishments:** Completed a research presentation. You can view the report in Chinese [here](https://jinyan-sivan.github.io/files/report.pdf).

### Drug-Interaction Prediction based on Chain-of-Thought Prompting in GPT3.5
_Supervisor_ : Prof. [Pengtao Xie](https://pengtaoxie.github.io/)
_June 2023 - October 2023_

- **Description:** In this project, I designed a series of logical steps named Chain-of-Thought (CoT) for the GPT intendvved for drug-interaction prediction. 
