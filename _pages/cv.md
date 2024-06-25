---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Skills
======

Programming
-----------
* Python
* C++
* Mathematica
Also [...]

Machine learning
----------------
* Pandas
* Scikit-learn
* Tensorflow

Research
--------


Work experience
======

* Postdoctoral Fellow (Technion), 2023-2024

* Research Assistant (King's College London), 2022-2023

* Postdoctoral Fellow (Perimeter Institute), 2022

* Postdoctoral Fellow (Institute for Theoretical and Mathematical Physics,
  Moscow), 2021-2022


* Teaching Assistant (King's College London), 2017-2021
    * Numerical methods
    * Advanced Quantum Mechanics
    * Calculus 1
    * Groups and Symmetries
    * Geometry of Surfaces
    * Dynamical Systems


Education
======
* PhD in Applied Mathematics: Theoretical Physics (King's College London), 2021
* MSc in Physics (Université Laval), 2017
* BSc in Physics (Université Laval), 2015

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
