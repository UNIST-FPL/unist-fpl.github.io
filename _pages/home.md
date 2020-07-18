---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#324dad" # "#5e616c"
  actions:
    - label: "Click to apply Ph.D./M.E./Internship programs"
      url: /apply/
excerpt: >
  Fusion and Plasma application research Laboratory <br /> <br />
  <small>Fusion and Plasma application research Laboratory aims at resolving various problems facing in successful nuclear fusion experiments and commercialization through plasma simulator development and simulations.</small> <br /> 
  <small>For more details of our research, see [Research](/research/). </small> <br />
---

<!--- The research includes Eulerian & Lagrangian code development based on Gyrokinetics and MHD (magneto-hydro dynamics), extension and improvement on theories and numerical methods for simulation of long time plasma behavior, code verification & validation, and parallel programming and code optimization to utilize the latest architectures being used in supercomputers. These research subjects allow us to carry out more realistic simulation of plasma behavior in nuclear fusion reactors considering impurities and consequently to clarify and exploit underlying physics of experimental results. --->

----

## Recent Postings
<div class="grid__wrapper">
  {% for post in site.posts limit:4 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

