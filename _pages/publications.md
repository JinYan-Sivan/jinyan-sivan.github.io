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
_Supervisor:_ Prof. [Zhenyu Yang](http://nanophotonics.oei.hust.edu.cn/info/1101/1183.htm) 
_September 2022 – January 2023_

- **Description:** Designed metalens to reconstruct the Stokes parametrization of light based on PB phase modulation, Hartmann-shack wavefront detection principle. The incident light intensity was detected by 4~6 different polarization-sensitive lenses to reconstruct the Stokes parameter of the incident light.
  
- **Tools:** Lumerical FDTD solutions, MATLAB, Python.

- **Accomplishments:** Completed a research presentation. You can view the report in Chinese [here](jinyan-sivan.github.io/files/report.pdf).
