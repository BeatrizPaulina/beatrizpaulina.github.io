---
layout: page
title: Research Projects
permalink: /projects/
---

# Prominent Research Projects

## Reconstruction, Characterization, and Diagnosis of Suspicious Objects or Unusual Events in Medical Images (CT, DS, MG) and Remote Sensing
**Institution:** Instituto Politécnico Nacional (IPN)

**Dates of Participation:** 2021-Current

**Description:** I currently collaborate on a research project to enhance the quality and efficiency of digital image processing in 2D/3D by implementing new theories and techniques, addressing specific issues across various applications such as medicine (DS, CT, MG, US images), natural resource monitoring via remote sensing, protected visualization of 3D objects, and copyright protection in digital audio signals and images. Implementation of developed techniques and optimization of software and hardware resources with a focus on real-time execution.

**Roles and Contributions:**
- Writing, translating, editing, and revising academic documents including articles, reports, presentations, and manuals.
- Algorithm replication in Python, Matlab, and C/C++.
- Programming of algorithms for execution in parallel and real-time architectures.
- Co-supervisor of undergraduate theses (Bachelor's Degree in Computer Engineering).
- Co-supervisor of postgraduate theses (Master of Science in Microelectronics Engineering and Ph. D. in Communications and Electronics).



## Research and Development of a Pipeline Monitoring System
**Collaborating Institutions:** Instituto Politécnico Nacional (IPN) in collaboration with the Mexican Petroleum Institute (governmental project).

**Dates of Participation:** 2018-2020

**Description:** Led a project team responsible for the research and development of a pipeline monitoring system. The project aimed to develop algorithms for fuel leak detection by analyzing pressure and acoustic signals.

**Roles and Contributions:**
- Project Leader.
- Member of the research team that analyzed pressure and acoustic signals to develop algorithms for leak detection.
- Data Scientist: Applied data cleansing, analysis, and visualization in Microsoft Excel, Matlab, and C++.
- Modeling of leak detection using machine learning techniques.
- Coordination of the programming and development team under the Scrum framework.
- Programming and integration of algorithms with a focus on data analytics.
- Communication with stakeholders from the Mexican Petroleum Institute and the Project Director from Instituto Politécnico Nacional.
- Monitoring and reporting of progress through written reports and presentations to stakeholders.
- Design and creation of software and methodology documentation.
- Technical support for implementing the software in Mexican Petroleum Institute facilities.

## Research for the Classification of Temporary Agricultural Crops in High-Resolution Images

**Collaborating Institutions:** Universidad La Salle in collaboration with the Instituto Nacional de Estadística y Geografía and the Consejo Nacional de Ciencia y Tecnología, funded by the Sector Fund CONACYT - INEGI (governmental project).

**Dates of Participation:** 2013

**Description:** I collaborated on a research project funded by the Sector Fund CONACYT - INEGI. The project aims to estimate the planted area of a region by classifying temporary agricultural crops using high-resolution images and intelligent computing techniques. The goal is to classify at least four different crops such as beans, wheat, yellow corn, and white corn.

**Roles and Contributions:**
- Team collaboration with graduate students in developing a dynamic library for a Microsoft Windows application supporting the national agriculture census.
- Design of the software module for analyzing color spaces and their impact on illumination changes for image processing.
- Experimental design to evaluate the correlation between components of color spaces and their relationship with feature extraction in satellite images.
- Design and creation of software and methodology documentation.

# Further Research Projects under institutional grant (IPN)

<table>
  {% for row in site.data.projects %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

