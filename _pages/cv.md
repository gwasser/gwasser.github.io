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
---------

**M.S. in Mathematics**, 2011
:   University of New Orleans, New Orleans, LA

**M.S. in Physics**, 2009
:   University of New Orleans, New Orleans, LA

**B.S. in Physics & Mathematics**, 2007
:   University of New Orleans, New Orleans, LA

    * Dual degrees

Work Experience
---------------

**Vulnerability Analyst** | October 2014 - May 2023
:   Software Engineering Institute, Carnegie Mellon University, Pittsburgh, PA

    * Analyzed software security and coordinated security updates with device manufacturers, developers and researchers; identifying CWEs, assigning CVEs, assigning CVSS score, etc.
    * Authored technical notes (CERT Vulnerability Notes) on software vulnerability disclosures (see: https://www.kb.cert.org/vuls/)
    * Standards work: Co-authored CERT Guide to Coordinated Vulnerability Disclosure and contributed to the CVSS 3.0 specification
    * Authored SEI blog posts on topics including reverse engineering and security with Rust programming language.
    * Development of reverse engineering tools such as Java extensions for Ghidra

**Adjunct Instructor** | September 2011 - October 2014
:   Various Institutions (ITT Technical Institute, Pittsburgh Technical College, Point Park University), Pittsburgh, PA

    * Taught courses including (varying by semester/quarter): mathematics (algebra, calculus), general physics, electronics (DC/AC), C++ and Java programming, linux operating system
    
**Instructor of Record / Teaching Assistant** | August 2009 - August 2011
:   University of New Orleans, New Orleans, LA

    * Taught general physics as instructor of record; additional duties teaching lab
    * Co-authored new lab manual series (1st and 2nd semester, both algebra- and calculus-based)
    * Graduate School Project: Quantum density operator methods for three-level atoms
    * Supervisor: Dr. Ashok Puri
  
**Research Fellow** | August 2007 - August 2009
:   University of New Orleans, New Orleans, LA

    * Graduate School Project: Investigating possible superconductive perovskite thin films via pulsed laser deposition
    * Duties included: producing samples in lab; analysis using SEM, ellipsometer, etc.; maintaining deposition equipment and managing lab
    * Supervisor: Dr. Leonard Spinu
  
  
Skills
------
* **Programming Languages**: Python 3, Haskell, C++ (Qt), Java, Rust, C
* **Operating Systems**: Linux (SUSE, Red Hat, Ubuntu), Windows
  * Experience maintaining RPM packaging for OpenSUSE especially using OpenSUSE Build Service (OBS)
* **Technical Writing**

Publications
------------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
-----
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
--------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
----------------------
* Green Party of the United States national steering co-chair, 2021-2023
