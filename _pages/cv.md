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
* Ph.D in CS, Cornell University, 2031 (expected)
* B.S. in EECS, UC Berkeley, 2026

Work experience
======
* Summer 2025: Firmware and DSP Intern @ HP Inc.
  * Refactoring of internal tools for Poly headsets

* 2024-2025: Research Intern @ UC Berkeley Sky Computing Lab
  * Fairness in multi-tennant systems for shared I/O paths
  * Edge Computing with TEEs and Ethereum
  * Code Optimization Agent for GitHub Repositories
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
actively working on it... :)

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Coursework
======
{% assign levels = "graduate,undergraduate" | split: "," %}
{% assign headings = "Graduate,Undergraduate" | split: "," %}
{% for level in levels %}{% assign groups = site.data.coursework[level] %}{% if groups and groups != empty %}
<p style="margin:0.4em 0 0;"><strong>{{ headings[forloop.index0] }}</strong></p>{% for group in groups %}{% if group.institution %}
<p style="margin:0.2em 0 0;"><em>{{ group.institution }}</em></p>{% endif %}
<ul style="margin:0.1em 0 0.3em;">{% for course in group.courses %}
<li style="margin-bottom:0.05em; line-height:1.3;">{{ course.number }} - {{ course.name }}{% if course.term %} ({{ course.term }}){% endif %}</li>{% endfor %}
</ul>{% endfor %}{% endif %}{% endfor %} -->

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
