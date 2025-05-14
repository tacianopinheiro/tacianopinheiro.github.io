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
* Spring 2024: Academic Pages Collaborator
  * Federal University of Cariri
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Leadership

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
