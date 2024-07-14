---
layout: cv
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

EDUCATION
======

**M.S. Applied Mathematics** • 2011
:   University of New Orleans • New Orleans, LA

* Concentration in Engineering and Applied Sciences

**M.S. Physics** • 2009
:   University of New Orleans • New Orleans, LA

* Concentration in Materials Science

**B.S. Physics & B.S. Mathematics** • 2007
:   University of New Orleans • New Orleans, LA
    * Dual degrees

WORK EXPERIENCE
======

**Vulnerability Analyst / Member of Technical Staff** • 10/2014 - 05/2023
:   CERT/CC Division, Software Engineering Institute, Carnegie Mellon University • Pittsburgh, PA

* **Vulnerability analysis and threat modeling**: analysis of reports of potential software vulnerabilities from independent researchers, typically in open source software components -- including identifying flaws using CWE, OWASP, etc.; assessing severity with CVSS, modeling threats with STRIDE, etc.; assigning CVEs; and coordinating vulnerability disclosure process with vendors using PGP and other tools; etc.
* **Authored ~150 CERT Vulnerability Notes** on software vulnerability disclosures, in coordination with researchers and product developers/vendors (see: https://www.kb.cert.org/vuls/)
* **Co-author of The CERT Guide to Coordinated Vulnerability Disclosure** (CERT/CC, 2017; https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=503330).
* **Developed and maintained internal tools** for vulnerability discovery and reverse engineering, including Kaiju extension for Ghidra in Java, and data analysis tools in Python for use in CERT Pharos
* **Self-directed analysis and research** and **authored professional blog posts** on topics in coordinated vulnerability disclosure, static code analysis, and Rust programming language & ecosystem security (see blog posts: https://insights.sei.cmu.edu/authors/garret-wassermann/)
* **Represented CERT/CC on CVSS SIG** and **contributed to the development of CVSSv3.0** (see: https://www.first.org/cvss/v3.0/specification-document)
* **Delivered presentations at conferences** on coordinated vulnerability disclosure and software security

**Adjunct Instructor** • 09/2011 - 10/2014
:   Various Institutions (ITT Technical Institute, Pittsburgh Technical College, Point Park University) • Pittsburgh, PA

* **Taught** courses including **programming (Java and C++), computer networking, Linux operating system, calculus, college algebra, physics**; varied by semester/quarter, about 5 courses per semester/quarter.
    
**Instructor of Record / Teaching Assistant** • 08/2009 - 08/2011
:   University of New Orleans, Department of Physics • New Orleans, LA

* **Taught** general physics lab and lecture courses
* **Co-authored** new physics lab curriculum and laboratory manual (1st and 2nd semester, both algebra- and calculus-based)
* Graduate School Project: Quantum density operator methods for three-level atoms
* Supervisor: Dr. Ashok Puri
  
**Research Fellow** • 08/2007 - 08/2009
:   University of New Orleans • New Orleans, LA

* Masters' Project: Investigating perovskite thin films produced via pulsed laser deposition for superconductivity
* Duties included: producing samples in lab; analysis using SEM, ellipsometer, etc.; maintaining deposition equipment and managing lab
* Supervisor: Dr. Leonard Spinu
  
  
CERTIFICATES
======

## Software Security & Engineering
* [Secure Coding Practices](http://gwasser.github.io/files/certificates/2024/Coursera UCDavis Secure Coding Practices Specialization Certificate.pdf) (Java/C/C++) Specialization Certificate, UC Davis via Coursera
* [JavaScript Security](http://gwasser.github.io/files/certificates/2024/Coursera InfoSec JavaScript Security.pdf) Specialization Certificate, InfoSec Institute via Coursera
* [OWASP Top 10 - 2021](http://gwasser.github.io/files/certificates/2024/Coursera InfoSec OWASP Top 10 2021.pdf) Specialization Certificate, InfoSec Institute via Coursera
* [Secure Software Design](http://gwasser.github.io/files/certificates/2024/Coursera University of Colorado Secure Software Design Specialization Certificate.pdf) Specialization Certificate, University of Colorado via Coursera

## Information Technology
* [CompTIA Security+ (Expired: Dec 2015)](http://gwasser.github.io/files/certificates/2012/CompTIA Security+ ce certificate.pdf)
* [CompTIA Linux+ (2013)](http://gwasser.github.io/files/certificates/2013/CompTIA Linux+ certificate.pdf)
* [SUSE Certified Linux Professional (2013)](http://gwasser.github.io/files/certificates/2013/GarretWassermann_SCLP_ECR.pdf)
* [Linux Professional Institute LPIC-1 (2013)](http://gwasser.github.io/files/certificates/2013/LPIC1-certificate.pdf)

## Science Journalism
* The Open Notebook - Science Journalism Master Classes (2024)
  - Classes included: [How To Find An Angle For Any Story](http://gwasser.github.io/files/certificates/2024/Certificate-of-Completion-TON-Angles-Course.pdf), [How To Spot Scientific Hype and Misinformation](http://gwasser.github.io/files/certificates/2024/Certificate-of-Completion-TON-Hype-Course.pdf), [How To Own A Science Beat](http://gwasser.github.io/files/certificates/2024/Certificate-of-Completion-TON-Beat-Course.pdf), [How To Center People In Science Stories](http://gwasser.github.io/files/certificates/2024/Certificate-of-Completion-TON-Centering-People-Course.pdf), [How To Ace The Study Story](http://gwasser.github.io/files/certificates/2024/Certificate-of-Completion-TON-Study-Story-Course.pdf)

## Ecology
* [EcoDistricts Accredited Professional (2020)](http://gwasser.github.io/files/certificates/2020/EcoDistricts AP Certificate Garret Wassermann.pdf)

SKILLS AND INTERESTS
======

* **Programming Languages**: Python 3, Haskell, C++ (Qt), Java, Rust, C
* **Operating Systems**: Linux (SUSE prefered, Red Hat, Ubuntu), Windows
  - Experience maintaining RPM packaging for OpenSUSE especially using OpenSUSE Build Service (OBS)
* **Technical Writing**

PUBLICATIONS
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
CONFERENCES
======

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
COURSES TAUGHT
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
