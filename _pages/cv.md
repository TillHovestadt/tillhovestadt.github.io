---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download
======

Download my full CV here:                    
<p><a href = "https://github.com/TillHovestadt/CV/raw/main/CV_Hovestadt_DE.pdf">German CV (Last changed: May 2024)</a></p>
<p><a href = "https://github.com/TillHovestadt/CV/raw/main/CV_Hovestadt_EN.pdf">English CV (Last changed: May 2024)</a></p>


Education
======
* Ph.D in Sociology, University of Oxford, 2024--
* M.A. in Sociology, Leipzig University, 2022
* B.A. in Sociology, Leipzig University, 2019
* B.Sc. in Psychology (first year), University of Groningen, 2016

Work experience
======
* 2022--2024: Research Associate
  * Leipzig University
  * Supervisor: [Dr. Georg Lorenz](https://www.uni-leipzig.de/en/profile/mitarbeiter/dr-georg-lorenz)

* 2017--2022: Research Assistant
  * Leipzig University
  * Supervisors: Prof. Dr. Thorsten Schneider, Prof. Dr. Roger Berger, Prof. Dr. em. Kurt Mühler, Dr. Melanie Olczyk

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
