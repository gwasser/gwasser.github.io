---
layout: cv
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

WORK EXPERIENCE
======

**Security Engineer, Vulnerability Management** • 10/2024 - Present
:   GitLab • Pittsburgh, PA (Remote)

* Implement new and iterate on existing technology to help identify and mitigate security issues.
* Build automation.
* Validate and triage identified vulnerabilities.
* Track remediation efforts to their completion.
* Contribute to team strategy in managing threats and vulnerabilities.
* Participate in rapid action efforts or other emergency response as needed.

**Vulnerability Analyst / Member of Technical Staff** • 10/2014 - 05/2023
:   CERT/CC Division, Software Engineering Institute, Carnegie Mellon University • Pittsburgh, PA

* **Vulnerability analysis and threat modeling**: analysis of reports of potential software vulnerabilities from independent researchers, typically in open source software components -- including identifying flaws using CWE, OWASP, etc.; assessing severity with CVSS, modeling threats with STRIDE, etc.; assigning CVEs; and coordinating vulnerability disclosure process with vendors using PGP and other tools; etc.
* **Authored ~150 CERT Vulnerability Notes** on software vulnerability disclosures, in coordination with researchers and product developers/vendors (see: [https://www.kb.cert.org/vuls/](https://www.kb.cert.org/vuls/))
* **Co-author of The CERT Guide to Coordinated Vulnerability Disclosure** (CERT/CC, 2017; see [the original report](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=503330), or the [updated web version](https://certcc.github.io/CERT-Guide-to-CVD/)).
* **Developed and maintained internal tools** for vulnerability discovery and reverse engineering, including Kaiju extension for Ghidra in Java, and data analysis tools in Python for use in CERT Pharos
* **Self-directed analysis and research** and **authored professional blog posts** on topics in coordinated vulnerability disclosure, static code analysis, and Rust programming language & ecosystem security (see blog posts: [https://insights.sei.cmu.edu/authors/garret-wassermann/](https://insights.sei.cmu.edu/authors/garret-wassermann/))
* **Represented CERT/CC on CVSS SIG** and **contributed to the development of CVSSv3.0** (see: [https://www.first.org/cvss/v3.0/specification-document](https://www.first.org/cvss/v3.0/specification-document))
* **Delivered presentations at conferences** on coordinated vulnerability disclosure and software security

**Adjunct Instructor** • 09/2011 - 10/2014
:   Various Institutions (ITT Technical Institute, Pittsburgh Technical College, Point Park University) • Pittsburgh, PA

* **Taught** courses including **programming (Java and C++), computer networking, Linux operating system, calculus, college algebra, physics, electronics**; varied by semester/quarter, about 5 courses per semester/quarter.
    
**Instructor of Record / Teaching Assistant** • 08/2009 - 08/2011
:   University of New Orleans, Department of Physics • New Orleans, LA

* **Taught** general physics lab and lecture courses
* **Co-authored** new physics lab curriculum and laboratory manual (1st and 2nd semester, both algebra- and calculus-based)
* **Developed simulations** for quantum optics problems in Python
* Graduate School Project: Quantum density operator methods for three-level atoms
* Supervisor: Dr. Ashok Puri
  
**Research Fellow** • 08/2007 - 08/2009
:   University of New Orleans • New Orleans, LA

* **Managed an experimental lab**: producing samples; analysis using electron microscope, ellipsometer, etc.; maintaining deposition equipment; training new users in sample preparation
* **Developed simulations** for magnetism in Fortran
* Masters' Project: Investigating perovskite thin films produced via pulsed laser deposition for superconductivity
* Supervisor: Dr. Leonard Spinu

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
  
CERTIFICATES
======

**Software Development Lifecycle (SDLC)** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera University of Minnesota SDLC Specialization.pdf) • 2024
:   University of Minnesota on Coursera

**Secure Software Design** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera University of Colorado Secure Software Design Specialization Certificate.pdf) • 2024
:   University of Colorado System on Coursera

**Python 3 Programming** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera University of Michigan Python 3 Programming Specialization.pdf) • 2024
:   University of Michigan on Coursera

**Programming in Go** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera UCIrvine Programming in Go Specialization.pdf) • 2024
:   University of California - Irvine on Coursera

**Secure Coding Practices (Java/C/C++)** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera UCDavis Secure Coding Practices Specialization Certificate.pdf) • 2024
:   University of California - Davis on Coursera

**JavaScript Security** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera InfoSec JavaScript Security.pdf) • 2024
:   InfoSec on Coursera

**OWASP Top 10 - 2021 List** [\[Link\]](http://gwasser.github.io/files/certificates/2024/Coursera InfoSec OWASP Top 10 2021.pdf) • 2024
:   InfoSec on Coursera

**Linux+** [\[Link\]](http://gwasser.github.io/files/certificates/2013/CompTIA Linux+ certificate.pdf) • 2013
:   CompTIA

**SUSE Certified Linux Professional** [\[Link\]](http://gwasser.github.io/files/certificates/2013/GarretWassermann_SCLP_ECR.pdf) • 2013
:   SUSE

**Linux Professional Institute LPIC-1** [\[Link\]](http://gwasser.github.io/files/certificates/2013/LPIC1-certificate.pdf) • 2013
:   Linux Professional Institute

**Security+** [\[Link\]](http://gwasser.github.io/files/certificates/2012/CompTIA Security+ ce certificate.pdf) • 2012 (Expired 2015)
:   CompTIA

SKILLS AND INTERESTS
======

* **Programming Languages**: Python, Go, Haskell, Rust, Java, C
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
