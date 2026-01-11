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
* Ph.D in Information Technology (Systems and Control), Politecnico di Milano, 2018
* M.S. in Automation Engineering, Politecnico di Milano, 2013
* B.S. in Mechatronics Engineering, Sabnci Universitesi, 2010

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* November 2017 - December 2019: Research Fellow
  * Politecnico di Milano

* PhD Student: November 2014 - Octobor 2017
  * Politecnico di Milano
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- 
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
-->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Projects
======
  <ul>{% for post in site.research_projects reversed %}
    {% include archive-single-research-projects-cv.html  %}
  {% endfor %}</ul>
