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
* PhD in Electrical Engineering, Indian Institute of Technology Gandhinagar, 2021–2026
  * GPA: 9.58/10. Guide: Prof. Nithin V. George
  * Thesis: Adaptive DOA Estimation and Region-of-Interest Beamforming using Microphone Array Systems
* Visiting Research Fellow, Electrical Engineering, Technion – Israel Institute of Technology, Aug 2024 – Jan 2025
* MTech in Electrical Engineering, National Institute of Technology Hamirpur, 2018–2020
  * GPA: 9.24/10. Program Rank 1, Gold Medal
* BTech in Electrical and Electronics Engineering, University of Kerala, 2013–2017
  * GPA: 9.4/10. Ranked 2nd among students across the university's 36 affiliated engineering colleges

Work experience
======
* Research Intern, Indian Institute of Technology Bombay
  * Project: Computational Modeling for Music Discovery

Teaching assistantship
======
* EE 609 – Advanced Signal Processing, IIT Gandhinagar
* ES 331 – Probability and Random Process, IIT Gandhinagar

Skills
======
* Programming: MATLAB (proficient), Python, C (basic)
* Domain: Adaptive filtering, beamforming, array signal processing, DOA estimation, acoustic/speech signal processing

Honours and awards
======
* ANRF International Travel Support (ITS) Scheme grant, INTER-NOISE 2025, Brazil
* IIT Gandhinagar Overseas Research Fellowship, Technion, Israel (6 months)
* Gold Medalist, MTech EE Department, National Institute of Technology Hamirpur
* 2nd Rank, BTech EEE, University of Kerala

Publications
======

Journal Articles
------
  <ul>{% assign journal_pubs = site.publications | where: "type", "journal" | sort: "date" | reverse %}{% for post in journal_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Conference Papers
------
  <ul>{% assign conference_pubs = site.publications | where: "type", "conference" | sort: "date" | reverse %}{% for post in conference_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
  <ul>{% assign sorted_patents = site.patents | sort: "date" | reverse %}{% for post in sorted_patents %}
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
  
Service and leadership
======
* Journal reviewer:
  * IEEE/ACM Transactions on Audio, Speech and Language Processing
  * IEEE Signal Processing Letters
  * IEEE Transactions on Vehicular Technology
  * Elsevier Signal Processing
  * IEEE Sensors Journal
  * IEEE Transactions on Circuits and Systems II: Express Briefs
