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
* Professor (2023-now)
* CIO (2021-now)
* IT Analyst (2013-now)
* :earth_americas: Juazeiro do Norte - CE - Brazil

**MAXCON Internet**
* Network consultant (2008-now)
* :computer: Remote 

**Ceará State University (UECE)**
* Professor (2013-2018)
* :earth_americas: Fortaleza - CE - Brazil

**Paraíso College (FAP)**
* Professor (2012-2016)
* :earth_americas: Juazeiro do Norte - CE - Brazil

**Federal University of Ceará (UFC)**
* IT Analyst (2011-2013)
* :earth_americas: Fortaleza - CE - Brazil
    
**Leão Sampaio College (FALS)**
* Professor (2011)
* :earth_americas: Juazeiro do Norte - CE - Brazil

**BRQ IT Services**
* IT consultant (2009-2010)
* :earth_americas: Fortaleza - CE - Brazil

**Stefanini IT Solutions**
* Software Engineer (2008-2009)
* :earth_americas: Fortaleza - CE - Brazil
  
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
