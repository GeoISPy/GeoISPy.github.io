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
* Ph.D in Wuhan University, 2026 (expected)
* B.S. in East China Normal University, 2020

Work experience
======
* Apr. ~ Sep. 2025: Academic Collaborator
  * South Korea Astronomy and Space Science Institute
  * Supervisor: Jaeheung Park
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
