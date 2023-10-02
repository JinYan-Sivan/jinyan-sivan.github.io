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

### Huazhong University of Science and Technology
_Wuhan, China_

**Research Assistant in Prof. Zhenyu Yang’s Group**  
_September 2022 – January 2023_

_Project:_ **Metalens-based Optical Multiparameter Detection**  
_Supervisor:_ Prof. Zhenyu Yang

- **Description:** Designed metalens to reconstruct the Stokes parametrization of light based on PB phase modulation, Hartmann-shack wavefront detection principle. The incident light intensity was detected by 4~6 different polarization-sensitive lenses to reconstruct the Stokes parameter of the incident light.
  
- **Tools:** Lumerical FDTD solutions, MATLAB, Python.

- **Accomplishments:** Completed a research presentation.
