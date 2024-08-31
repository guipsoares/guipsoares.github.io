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
* B.S. in Statistics and Data Science
  * University of Sao Paulo
  * 2022-2025 (expected)
  * GPA: 9.3/10 (rank 1/45)

Work experience
======
* Jan - Dec 2024: Research Assistant
  * **King Abdullah University of Science and Technology (KAUST)**
  * I received the Visiting Student Research Program Fellowship to spend a semester at [GeoHealth Lab](https://cemse.kaust.edu.sa/geohealth), where I was advised by Professor [Paula Moraga](https://www.paulamoraga.com/). We developed statistical and machine learning methods to forecast dengue in Brazil. Some preliminary results can be found [here](https://diseasesurveillance.github.io/dengue-tracker/index.html). We also collaborated with other researchers from different countries (e.g., China, Costa Rica, and Brazil). My contract was initially until June, but I was offered an extension to work remotely until December to extend the work to other countries.

* Jan 2023 - Present: Research Assistant
  * **Statistical Machine Learning Lab - SMaLL - UFSCar**
  * Undergraduate researcher at [SMaLL](http://www.small.ufscar.br), advised by Professor [Rafael Izbicki](https://rafaelizbicki.com/). I've worked with data from the Brazilian Ministry of Health, mainly processing it and analyzing the performance of our nowcasting model on severe acute respiratory diseases. This work resulted in one workshop paper presented at IWSM 2024 in Durham.
  * I've recently been working with Conformal Prediction methods for Likelihood-Free Inference problems. Updates on this soon!
  
* Jul 2022 - Dec 2023: Data Science Intern
  * **Big Data**
  * Creation of pipelines with Python and its libraries like pandas, sklearn, statsmodels, etc, most of them related to                Experimentation and Machine Learning Engineering
  * Worked on the Experimentation squad, mainly with A/B testing and sampling
  * Based on a problem with the method of sampling the TG/CG, I helped develop a new tool based on the
        bootstrapping technique, stratifying points of sales taking into account business rules in order to maximize the
        upside in the desired metric (e.g., gross revenue)
  * I was one of the maintainers of the Experimentation internal package
  * I developed Airflow DAGs to extract, transform, and load data - usually from AWS S3 to Postgres databases.

Skills
======
* Coding
  * Advanced: Python, R, SQL, Shell Script
* Developing tools
  * Advanced: Git, Markdown, Linux
  * Intermediate: Latex, Airflow, Docker
* Languages:
  * Portuguese: Native
  * English: Fluent
  * Spanish: Intermediate

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
