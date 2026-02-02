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
* Ph.D in Cybersecurity, [Your University], [Year] - Present
  * Research focus: [Your Research Topic]
* M.S. in [Your Field], [Your University], [Year] - [Year]
* B.S. in [Your Field], [Your University], [Year] - [Year]

Work experience
======
* [Current Position/Year]: [Position Title]
  * [Company/University]
  * Duties included: [Description of responsibilities]
  * Supervisor: [Supervisor Name]

* [Previous Position/Year]: [Position Title]
  * [Company/University]
  * Duties included: [Description of work]
  * Supervisor: [Supervisor Name]
  
Skills
======
* Programming Languages
  * Python
  * C/C++
  * Java
  * JavaScript
* Cybersecurity
  * Network Security
  * Cryptography
  * Penetration Testing
  * Reverse Engineering
* Tools & Technologies
  * Wireshark
  * Burp Suite
  * Git
  * Linux/Unix

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
