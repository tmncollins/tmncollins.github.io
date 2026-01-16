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
* MSci Chemistry, University of Cambridge, 1st Class, 2026 (expected)
* BA (Hons) Natural Sciences - Chemistry, University of Cambridge, 1st Class, 2025

Work experience
======
* Spring 2026: Academic Pages Collaborator
  * Balasubramanian Lab, Cambridge
  * Developed Machine Learning program for predicting non-canonical DNA structures, involving coding, training, and testing the model
  * Employed methods for neural network interpretation to better understand the factors controlling DNA structure.
  * Synthesised DNA oligomers using solid-phase phosphoramidite chemistry and characterised their structure to confirm the accuracy of my ML model

* Summer 2025: High-Throughput Chemist
  * ReactWise, Cambridge
  * Developed and executed high-throughput workflows to run and analyse over 5000 miniaturised reactions
  * Programmed automated OpenTrons liquid handlers and Agilent Infinity UHPLC-MS equipment in Python 3
  * Employed Bayesian Optimisation and Design of Experiment to optimise reaction conditions to maximise yield and minimise impurities
  * Analysed, cleaned, and visualised data to produce a high-quality bespoke dataset for Machine Learning
  * Understood start-up culture, organisation, and strategy at the frontier of chemical research

* Summer 2024: Biochemistry Researcher
  * Knowles Group, Cambridge
  * Analysed interactions between medicinal iron nano-particles and human blood proteins under a range of physiological conditions
  * Designed and executed detailed experimental plans using AKTA protein purification and CD scans
  * Interpreted novel results using Excel and Python and rationalised the result with the surrounding literature
  
Skills
======
* Programming Languages
  * Python
  * C++
  * Java
* Computational Work
  * Machine Learning
  * Deep Learning
  * Monte-Carlo Simulation
  * Markov Chains
  * Bayesian Optimisation
* Lab Work
  * NMR
  * Protein Purification
  * High-Throughput Experimentation
  * Automated Liquid Handling
  * UHPLC-MS

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
