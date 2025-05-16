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
* :mortar_board: Graduate Certificate in Privacy and Information Security, University of Brasília, 2026 (expected)
* :mortar_board: M.S. in Applied Computing, Ceará State University, 2012
* :mortar_board: B.S. in Computer Science, Federal University of Campina Gande, 2008

Work experience
======

**Federal University of Cariri (UFCA)**
:earth_americas: Juazeiro do Norte - CE - Brazil
* Professor (2023-now)
* CIO (2021-now)
* IT Analyst (2013-now)

**MAXCON Internet**
:computer: Remote 
* Network consultant (2008-now)
  * Planning, expansion, operation, and support of the telecommunications network of an Internet Service Provider (ISP).

**Ceará State University (UECE)**
:earth_americas: Fortaleza - CE - Brazil
* Professor (2013-2018)
  * Taught undergraduate courses in the Bachelor's degree program in Computing Education.

**Paraíso College (FAP)**
:earth_americas: Juazeiro do Norte - CE - Brazil
* Professor (2012-2016)
  * Taught undergraduate courses in the Bachelor's degree program in Information Systems.

**Federal University of Ceará (UFC)**
:earth_americas: Fortaleza - CE - Brazil
* IT Analyst (2011-2013)
  * Systems analysis and development for learning management systems (LMS) of the Virtual University Institute (UFC-Virtual) at the Federal University of Ceará.
    
**Leão Sampaio College (FALS)**
:earth_americas: Juazeiro do Norte - CE - Brazil
* Professor (2011)
  * Taught undergraduate courses in the Associate degree program in Systems Analysis and Development.

**BRQ IT Services**
:earth_americas: Fortaleza - CE - Brazil
* IT consultant (2009-2010)
  * Systems Analysis and Development for the health insurance provider Unimed Fortaleza

**Stefanini IT Solutions**
:earth_americas: Fortaleza - CE - Brazil
* Software Engineer (2008-2009)
  * Systems Analysis and Design for the health insurance provider Unimed Fortaleza.
  
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
