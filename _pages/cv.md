---
layout: single
title: "CV"
classes: wide
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
----
* 2019 - Ph.D. in Structural Biology, Stanford University,
* 2013 - B.S. in  Molecular, Cell and Developmental Biology, University of California, Los Angeles


Research Experience
----
* 2023 - Present: NIGMS K99 Fellow
    * UC Berkeley, Hosted by Yun S. Song and David F. Savage
    * Using machine learning to create better models of the sequence/structure/function relationship in proteins
    
* 2020 - 2023: Miller Fellow
    * Hosted by Yun S. Song, UC Berkeley
    * Using machine learning to create better models of the sequence/structure/function relationship in proteins

* 2013 - 2019: Ph.D. Student
    * Lab of Brian Kobilka, Stanford University
    * Structural basis of activation and signaling in GPCRS:
        * Structure of the &mu; opioid receptor in complex with the G protein Gi
        * Structural basis of activation of the family C GPCR, mGlu5

* Summer 2012: Amgen Scholar
    * Lab of Andre Hoelz, Caltech
    * Expression, purification and crystallization of the large nucleoporin Nup192, a component of the nuclear pore complex

* 2011 - 2013: Undergraduate Researcher
    * Pascal Egea Lab, UCLA
    * Expression, purification and crystallization of ClpB and ClpS N-terminal domains from Plasmodium falciparum
    * Structures provided insights into the mechanism of substrate recognition and discrimination

* Summer 2011: Undergraduate Research Assistant
  * Shimon Weiss/Feng Guo Labs, UCLA
  * Used a fluorescence based assay to measure activity of Drosha/DGCR8 complex in microRNA processing

* Summer 2010: Undergraduate Research Assistant
  * National University of Singapore
  * qPCR analysis of differentially expressed cancer genes following HepB infection

Academic Honors
---
* K99/R00 Pathway to Independence Award
    * NIH/NIGMS
* Miller Fellowship
    * Miller Institute for Basic Science in Research
* Amgen Scholarship
    * Amgen Foundation
    
Publications
----
  <ul>{% assign sorted = site.publications | sort: "pub_date" | reverse %}
      {% for post in sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  
