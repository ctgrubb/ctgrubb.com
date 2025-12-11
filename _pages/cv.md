---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Statistics, Virginia Tech, 2023
* B.S. in Mathematics, Millersville University, 2016

Work experience
======
* ***Research Scientist*, Center for Biostatistics and Health Data Science** (Aug 2023 - Present). Help medical student students with statistics within research domain projects. Assist faculty researchers within the medical school and affiliated researchers with NIH grant submissions and research projects. Host drop-in hours for statistical support available to medical school students as well as students and faculty from the university at large.
* ***Lead Collaborator*, Statistical Applications and Innovations Group** (May 2017 - May 2021). Helped approximately 100 graduate students and university faculty with statistics important for their masters' theses, dissertations, or publications. Taught several short courses (virtual and in-person) on base R graphics, R graphics using `ggplot2`, categorical data analysis, and regression and ANOVA. I also worked on a number of special long-term projects and/or grants:
	1. *Lung Health Sensors* (05/2021 - 05/2022). Fit random-effcts linear models and performed sensitivity analysis for a grant project focused on finding a ventilator that inflicts less lung damage from long-term use. 
	2. *VT Covid-19 Wastewater Monitoring* (09/2020 - 05/2021). Automated the gathering and merging of various data sources that updated daily, twice weekly, and weekly, while remaining HIPAA compliant. Investigated the relationship between virus shed in wastewater and outbreaks within university dormitories using generalized linear mixed effects models.
	3. *VT Advancement* (12/2019 - 06/2020). Developed a codebase to automate data cleaning, feature synthesis, modeling, prediction, and report generation with the end goal of highlighting university alumni more likely to engage (donate to university, attend university events, etc) so that resources could be allocated more effectively.
* ***Data Science Intern*, Microsoft** (Summer, 2019). Implemented deep feature synthesis for a then-unreleased product that became Power BI's Cognitive Services, an AutoML solution designed for corporations with little to no statistical or machine learning knowledge. 
* ***Data Science Intern*, Microsoft** (Summer, 2018). Used market basket analysis to investigate the predictive power of transactional history within a recommender system for Xbox Store. Was required to learn a proprietary query language (SCOPE) that evolved into U-SQL.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

