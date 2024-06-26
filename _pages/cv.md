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
* *Ph.D. in Computer Science* (cotutelle), **Université de Sherbrooke** / **INSA Lyon**, *2020-2024*  
Supervisors: [Pierre-Marc Jodoin](https://info.usherbrooke.ca/pmjodoin/index.html), [Olivier Bernard](https://www.creatis.insa-lyon.fr/~bernard/index.html), [Nicolas Duchateau](https://www.creatis.insa-lyon.fr/~duchateau/)  
[Link to thesis manuscript](http://hdl.handle.net/11143/21647) | [Link to thesis defense recording]( https://youtu.be/jqbe2wLzJYU)

* *M.Sc. in Computer Science*, **Université de Sherbrooke**, *2019-*  
Supervisor: [Pierre-Marc Jodoin](https://info.usherbrooke.ca/pmjodoin/index.html)

* *B.Sc. in Computer Science*, **Université de Sherbrooke**, *2016-2019*

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

Work Experience
======
* *Summer 2019*: **[CREATIS](https://www.creatis.insa-lyon.fr/site7/en) (Biomedical imaging research laboratory)**  
*Invited student researcher*  
Supervisor: [Olivier Bernard](https://www.creatis.insa-lyon.fr/~bernard/index.html)
  * **Duties included**: Generalizing an anatomically-consistent segmentation method, first developed for cardiac cine-MRI, to echocardiography

* *Summer 2018*: **[GRIIS](https://griis.ca) (Interdisciplinary Research Group in Health Informatics)**  
*Backend developer* (Intern)  
Supervisor: [Luc Lavoie](http://info.usherbrooke.ca/llavoie/)
  * **Duties included**: Specifying and validating software requirements, design and test-driven implementation of internal APIs

&nbsp;

Service and Volunteer Work
======
* *2021-2023*: **Université de Sherbrooke** / **École de technologie supérieure (ETS)** / **CREATIS**  
*Hands-on Supervisor for the Deep Learning for Medical Imaging School*
  * **Duties included**: Preparing administrative and scientific content (video tutorials, interactive exercises, etc.), organizing and moderating hands-on sessions

* *June 2023*: **Functional Imaging and Modeling of the Heart (FIMH)**  
*Student volunteer for the organization of the conference*
  * **Duties included**: Administrative and manual labor during the conférence, such as: recording of keynote and oral presentations, setting up the venue, greeting attendees, etc.

* *2022*: **CREATIS**  
*Organizer of the doctoral day for 3rd year Ph.D. students*
  * **Duties included**: Communication with the participants (call for presentations, etc.), preparing the schedule, preparing the location and material (checking material for the presentations, testing auditorium setup, etc.), and coordinating the presentations on the day of

* *2021-2022*: **Université de Sherbrooke**  
*Scholarships applications support*
  * **Duties included**: Helping graduate students prepare their scholarships applications

* *2020-2021*: **Université de Sherbooke**  
*Medical imaging student committee*
  * **Duties included**: Organizing events for the community of graduate students in medical imaging

* *2018-2021*: **Université de Sherbrooke**  
*Student representative for promotional events*
  * **Duties included**: Recruitment of prospective students
