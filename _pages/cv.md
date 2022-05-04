---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Electromechanical Engineering, National University of Central Buenos Aires, 2015
* Ph.D in Engineering, National University of Central Buenos Aires, 2019

Work experience
======
* 2021-Current: Research Assistant
  * The University of Edinburgh
  * Duties included: Research, supervising students
  * Supervisor: Dr. Stefano V. Albrecht

* 2020-2021: Research Assistant
  * Louisiana State University
  * Duties included: Research, teaching, supervising students
  * Supervisor: Dr. Corina Barbalata

* 2015-2020: PhD Researcher
  * National University of Central Buenos Aires
  * Duties included: Research
  * Supervisor: Dr. Gerardo G. Acosta

Teaching
======
    <ul>{% for post in site.teaching  reversed  %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>

Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
