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
* PhD in Statistics, Virginia Tech, May 2023 (expected)
* B.S. in Mathematics, Millersville University, 2016

Work experience
======
* ***Lead Collaborator***, Statistical Applications and Innovations Group (May 2017 - May 2021)
	Helped approximately 100 graduate students and university faculty with statistics important for their masters' theses, dissertations, or publications. Taught several short courses (virtual and in-person) on base R graphics, R graphics using `ggplot2`, categorical data analysis, and regression and ANOVA. 
	Worked on a number of special projects and/or grants:
	1. Grant - Lung Health Sensors (05/2021 - 05/2022)
	2. Special - VT Covid-19 Wastewater Monitoring
* Data Science Intern, Microsoft (Summer, 2019)
	Testing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

