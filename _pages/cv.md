---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

- [Education](#education)
- [Scholarships & Awards](#scholarships--awards)
- [Publications](#publications)
  - [Journal Papers](#journal-papers)
  - [Conference Papers](#conference-papers)
- [Reviews](#reviews)
- [Teaching](#teaching)
  - [Teaching Assistant](#teaching-assistant)
- [Work Experience](#work-experience)
- [Service and Volunteer Work](#service-and-volunteer-work)

&nbsp;

Education
======
* *Ph.D. in Computer Science* (Joint Ph.D.), **Université de Sherbrooke** / **INSA Lyon**, *2020-2024*  
**Subject**: Deep manifold learning for improved high blood pressure characterization using echocardiography  
**Supervisors**: [Pierre-Marc Jodoin](https://info.usherbrooke.ca/pmjodoin/index.html), [Olivier Bernard](https://www.creatis.insa-lyon.fr/~bernard/index.html), [Nicolas Duchateau](https://www.creatis.insa-lyon.fr/~duchateau/)  
[Link to thesis manuscript](http://hdl.handle.net/11143/21647) | [Link to thesis defense recording]( https://youtu.be/jqbe2wLzJYU)

* *M.Sc. in Computer Science*, **Université de Sherbrooke**, *2019-*  
**Subject**: Segmentation of MRI and ultrasound cardiac medical images with anatomical guarantees  
**Supervisor**: [Pierre-Marc Jodoin](https://info.usherbrooke.ca/pmjodoin/index.html)

* *B.Sc. in Computer Science*, **Université de Sherbrooke**, *2016-2019*

&nbsp;

Work Experience
======
* *Postdoctoral researcher*, **[CREATIS](https://www.creatis.insa-lyon.fr/site7/en) (INSA Lyon)** / **[LIX](https://www.lix.polytechnique.fr) (École polytechnique)** / **[ICube](https://icube.unistra.fr) (Université de Strasbourg)**, *2024-*  
**Subject**: Multimodal learning on graphs and clinical data for pulmonary embolism risk stratification models
**Supervisors**: [Odyssée Merveille](https://www.creatis.insa-lyon.fr/~merveille/), [Johannes Lutzeyer](https://johanneslutzeyer.com), [Thomas Lampert](https://sites.google.com/site/tomalampert/home)

* *Invited student researcher*, **[CREATIS](https://www.creatis.insa-lyon.fr/site7/en)**, *Summer 2019*  
**Subject**: Generalizing an anatomically-consistent segmentation method, first developed for cardiac cine-MRI, to echocardiography  
**Supervisor**: [Olivier Bernard](https://www.creatis.insa-lyon.fr/~bernard/index.html)

<!-- * *Backend developer (Intern)*, **[GRIIS](https://griis.ca) (Interdisciplinary Research Group in Health Informatics)**, *Summer 2018*  
**Subject**: Specifying and validating software requirements, design and test-driven implementation of internal APIs  
**Supervisor**: [Luc Lavoie](http://info.usherbrooke.ca/llavoie/) -->

&nbsp;

Scholarships & Awards
======
* **Scientific distinction**, *December 2023*  
*INSA Lyon*

* [**Louis-Berlinguet "Relève étoile" Award**, *April 2023*](https://frq.gouv.qc.ca/en/story-and-report/releve-etoile-louis-berlinguet-avril-2023/)  
*Fonds de Recherche - Nature et Technologies* (FRQNT)

* [**Thesis funding**, *2022-2023*](https://primes.universite-lyon.fr/labex-primes/site-francais/navigation/recherche/wp-4-traitement-d-images-multidimensionnelles-/nathan-painchaud-2020-2023-apprentissage-profond-de-varietes-pour-une-meilleure-caracterisation-de-l-hypertension-arterielle-en-imagerie-echocardiographique-197031.kjsp)  
[*LabEx PRIMES*](https://primes.universite-lyon.fr)

* **Canada Graduate Scholarship – Doctorate (CGS D)**, *2021-2024*  
*Natural Sciences and Engineering Research Council of Canada* (NSERC)

* **Doctoral training scholarship**, *2021-2025*  
*Fonds de Recherche - Nature et Technologies* (FRQNT)

* [**Hydro-Québec merit scholarship** (declined), *2021-2024*](https://www.usherbrooke.ca/recherche/etudier/pourquoi-choisir-udes/programmes-bourses/excellence/titulaires/hiver-2021)  
*Université de Sherbrooke*

* **Scholarship for Doctoral level study**, *2020-2022*  
[*Fondation Arbour*](https://www.fondationarbour.com/en/)

* **R3D Conseil inc. scholarship**, *2020*  
*Université de Sherbrooke*

* **Alexander Graham Bell Canada Graduate Scholarship - Master's (CGS M)**, *2019-2020*  
*Natural Sciences and Engineering Research Council of Canada* (NSERC)

* **Master's training scholarship**, *2019-2021*  
*Fonds de Recherche - Nature et Technologies* (FRQNT)

* [**Graduate studies merit scholarship** (declined), *2019-2021*](https://www.usherbrooke.ca/recherche/etudier/pourquoi-choisir-udes/programmes-bourses/excellence/titulaires/hiver-2019)  
*Université de Sherbrooke*

* **Canada Graduate Scholarships – Michael Smith Foreign Study Supplements (CGS-MSFSS)**, *2019*  
*Natural Sciences and Engineering Research Council of Canada* (NSERC)

* [**Gérard-Houdeville award**, *2019*](https://www.usherbrooke.ca/informatique/actualites/prix-et-distinctions/mentions-excellence)  
*Université de Sherbrooke*

&nbsp;

Publications
======

## Journal Papers
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'journal' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

## Conference Papers
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'proceedings' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

&nbsp;

Reviews
======
Reviewer for top-tier journals in artificial intelligence and medical imaging:
* [IEEE Transactions on Pattern Analysis and Machine Intelligence](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)
* [IEEE Transactions on Medical Imaging](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=42)
* [Artificial Intelligence in Medicine](https://www.sciencedirect.com/journal/artificial-intelligence-in-medicine)
* [IEEE Transactions on Biomedical Engineering](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10)
* [IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=58)
* [Scientific Reports](https://www.nature.com/srep/)
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->

&nbsp;

Teaching
======

## Teaching Assistant

  <ul>{% for post in site.teaching reversed %}
    {% if post.role == 'TA' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

&nbsp;

Service and Volunteer Work
======
* *Scientific committee*, **Deep Learning for Medical Imaging School (DLMI)**, *2021-*  
**Partner institutions**: *CREATIS*, *Université de Sherbrooke*, *École de technologie supérieure (ETS)*  
**Duties included**: Deciding on the program of the school, preparing administrative and scientific content (video tutorials, interactive exercises, etc.), organizing and moderating hands-on sessions

* *Volunteer for the conference*, **Functional Imaging and Modeling of the Heart (FIMH)**, *June 2023*  
**Duties included**: Administrative and manual labor during the conférence, such as: recording of keynote and oral presentations, setting up the venue, greeting attendees, etc.

* *Organizer of a doctoral symposium for Ph.D. students*, **CREATIS**, *2022*  
**Duties included**: Communication with the participants (call for presentations, etc.), preparing the schedule, preparing the location and material (checking material for the presentations, testing auditorium setup, etc.), and coordinating the presentations on the day of

* *Scholarships applications support*, **Université de Sherbrooke**, *2021-2022*  
**Duties included**: Helping graduate students prepare their scholarships applications

* *Medical imaging student committee*, **Université de Sherbooke**, *2020-2021*  
**Duties included**: Organizing events for the community of graduate students in medical imaging

* *Student representative for promotional events*, **Université de Sherbrooke**, *2018-2021*  
**Duties included**: Recruitment of prospective students
