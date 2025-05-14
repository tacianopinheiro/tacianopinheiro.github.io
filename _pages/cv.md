---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% if site.author.lattes %}
  <div class="wordwrap">You can also find my CV on <a href="{{site.author.lattes}}">Brazilian Academic CV Lattes</a>.</div>
{% endif %}

Education
======
* Graduate Certificate in Privacy and Information Security, University of Brasília, 2026 (expected)
* M.S. in Applied Computing, Ceará State University, 2012
* B.S. in Computer Science, Federal University of Campina Gande, 2008

Work experience
======
* IT Analyst (2011-now)
  * Federal University of Cariri
  * Duties includes: CIO (2021-now), IT Analyst (2011-now), Professor (2023-now)

* Network consultant (2008-now)
  * MAXCON Internet
  * Duties included: ISP operations.

* Professor (2013-2018)
  * Ceará State University
  * Duties included: Taught undergraduate courses.

* Professor (2012-2016)
  * Paraíso College
  * Duties included: Taught undergraduate courses.

* Professor (2011)
  * Leão Sampaio College
  * Duties included: Taught undergraduate courses.

* IT consultant (2009-2010)
  * BRQ IT Services
  * Duties included: Systems Analysis and Design for a Health Insurance Provider

* Software Engineer (2008-2009)
  * Stefanini IT Solutions
  * Duties included: Systems Analysis and Development for a Health Insurance Provider
  
Skills
======
* Leadership
* Coomunication

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
