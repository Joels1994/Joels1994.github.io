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
  * Research area: Time-Domain Region-of-Interest Beamforming
* MTech in Electrical Engineering, National Institute of Technology Hamirpur, 2018–2020
  * GPA: 9.24/10. Program Rank 1, Gold Medal
* BE (Hons.) in Electrical and Electronics Engineering, University of Kerala, 2013–2017
  * GPA: 9.4/10. University Rank 2 (among 36 colleges)

Research projects
======
* **Time-Domain Region-of-Interest Beamforming for Spatial Audio** — Signal and Image Processing Lab, Technion, with Prof. Israel Cohen. Developed a generalized sidelobe canceller (GSC) framework for time-domain region-of-interest beamforming with a microphone array, published in IEEE TASLP.
* **Ground-Based Source Localization using Planar Antenna Array on board a LEO Satellite** — Audio Signal Processing Lab, IIT Gandhinagar, with Space Application Center, Ahmedabad. Geolocation of a ground-based emitter using a planar array on a LEO satellite under strict size/weight/power constraints.
* **Coarray LMS: Adaptive Underdetermined DOA Estimation with Increased Degrees of Freedom** — Audio Signal Processing Lab, IIT Gandhinagar. A computationally efficient adaptive algorithm resolving more sources than sensors, using second-order statistics with the LMS principle; includes a polynomial-rooting variant.
* **Adaptive Low-Rank DOA Estimation using Complex Kronecker Product Decomposition** — Audio Signal Processing Lab, IIT Gandhinagar. Decomposes large DOA-estimating filter weights into smaller weights via complex Kronecker product decomposition, updated with NLMS/RLS, for faster convergence at lower computation.

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
* Domain: Adaptive filtering, beamforming, array signal processing, DOA estimation, acoustic/speech signal processing, Monte-Carlo simulation
* Operating systems: Windows, Linux

Honours and awards
======
* Viterbi Fellowship for Visiting Research at Technion – Israel Institute of Technology, Haifa, Israel
* ANRF International Travel Support (ITS) Scheme grant, INTER-NOISE 2025, Brazil
* IIT Gandhinagar Overseas Research Fellowship, Technion, Israel (6 months)
* PhD Research Fellowship, Ministry of Human Resource Development, Government of India (2021–)
* Postgraduate Research Fellowship, Ministry of Human Resource Development, Government of India (2018–2020)
* Gold Medalist, MTech EE Department, National Institute of Technology Hamirpur
* 2nd Rank, BTech EEE, University of Kerala

Publications
======
  <ul>{% for post in site.publications %}
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
* Journal reviewer: IEEE/ACM Transactions on Audio, Speech and Language Processing; IEEE Signal Processing Letters; IEEE Transactions on Vehicular Technology; Elsevier Signal Processing; IEEE Sensors Journal; IEEE Transactions on Circuits and Systems II: Express Briefs
