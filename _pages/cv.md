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
<div class="wordwrap">
  You can also find my CV on <a href="{{site.author.lattes}}">Brazilian Academic CV Lattes</a>.
</div>
{% endif %}

## 🎓 Education

* 🎓 **Graduate Certificate** in Privacy and Information Security, University of Brasília (expected 2026)
* 🎓 **M.S.** in Applied Computing, Ceará State University (2012)
* 🎓 **B.S.** in Computer Science, Federal University of Campina Grande (2008)

---

## 💼 Work Experience

### **Federal University of Cariri (UFCA)**  
📍 Juazeiro do Norte, CE – Brazil  
* Chief Information Officer (2021–Present)  
* Professor (2023–Present)  
* IT Analyst (2013–Present)

### **MAXCON Internet**  
🌐 Remote  
* Network Consultant (2008–Present)  
  * Planning, expansion, operation, and support of the telecommunications network of an Internet Service Provider (ISP)

### **Ceará State University (UECE)**  
📍 Fortaleza, CE – Brazil  
* Professor (2013–2018)  
  * Taught undergraduate courses in the **Bachelor’s in Computing Education**

### **Paraíso College (FAP)**  
📍 Juazeiro do Norte, CE – Brazil  
* Professor (2012–2016)  
  * Taught undergraduate courses in the **Bachelor’s in Information Systems**

### **Federal University of Ceará (UFC)**  
📍 Fortaleza, CE – Brazil  
* IT Analyst (2011–2013)  
  * Systems analysis and development for Learning Management Systems (LMS) at UFC Virtual (Virtual University Institute)

### **Leão Sampaio College (FALS)**  
📍 Juazeiro do Norte, CE – Brazil  
* Professor (2011)  
  * Taught undergraduate courses in the **Associate Degree in Systems Analysis and Development**

### **BRQ IT Services**  
📍 Fortaleza, CE – Brazil  
* IT Consultant (2009–2010)  
  * Systems analysis and development for the health insurance provider **Unimed Fortaleza**

### **Stefanini IT Solutions**  
📍 Fortaleza, CE – Brazil  
* Software Engineer (2008–2009)  
  * Systems analysis and design for the health insurance provider **Unimed Fortaleza**

---

## 🛠️ Skills

* Leadership  
* Communication

---

## 📚 Publications

<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

---

## 🎤 Talks

<ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>

---

## 👨‍🏫 Teaching

<ul>
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

---

## 🤝 Service and Leadership

* Currently signed in to 43 different Slack teams
