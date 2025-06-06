---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education #
### PhD Pharmacy and Biomedical Sciences, University of Strathclyde, 2019 - 2024 ##
_Thesis title: 'Novel Devices for Evaluating Nanomedicine Biological Fate’_ <br/>
Protein corona formation in vivo is a phenomenon of high current interest in pharmaceutical sciences; developing further understanding would accelerate the successful clinical translation of novel nanomedicines.
  *	Developed novel analytical methodologies (NTA, RMM) to assess changes in nanoparticle physicochemical characteristics following protein corona formation. <br/>
  *	Used advanced statistics including 3-way ANOVA to identify temperature, concentration and temporal effects on protein corona formation around polymeric nanoparticles.  <br/>
  *	Identified key parameters from a dataset derived from Computational Fluid Dynamics simulations using Principal Component Analysis. These parameters were later influential for the design of a 3D-printed microfluidic device capable of subjecting nanoparticles to physiologically relevant forces.<br/> 

Thesis abstract available [here](/phd-abstract/) <br/>
Data underpinning the thesis available [here](https://doi.org/10.15129/0c656eea-2d11-4e79-abed-d792195f90fc) 

### PG Certificate in Researcher Professional Development, University of Strathclyde, 2020 - 2022 <br/> ##
  A 60-credit qualification, achieved by undertaking activities that cover all 4 domains of the Researcher Development Framework. 

### MSc (by Research) Chemistry, University of York, 2016 - 2017 ##
_Thesis title: ‘Structure-Activity Relationships in Self-Assembled Heparin-Binding Nanostructures’_
 * Synthesised a family of palmitic acid-based self-assembling lipopeptides. Confirmed their identity _via_ a number of analytical methods including Mass Spectrometry, NMR and IR Spectroscopy. <br/>
  * Studied their self-assembly and binding of DNA and heparin sulfate using competition assays, Transmission Electron Microscopy and Circular Dichroism. <br/>

Thesis available [here](https://etheses.whiterose.ac.uk/20048/)

### BSc (hons) Chemistry, University of Sheffield, 2012 - 2016 ##
Modules covered Inorganic, Organic and Physical Chemistry, with a specific focus on polymer and colloid chemistry. <br/>
* First year modules included 40 credits of classes in German through the Modern Languages Teaching Centre at the University of Sheffield. These included a peer tandem module and a self directed research module which culminated in a 1500 word essay in German discussing whether the chemist Fritz Haber could be considered to be "evil" due to the role he played within the development of chemical weapons, and subsequent use of Zyklon B during WWII. <br/>
* Final year included a 3000-word Literature Review on “Magnetic Particle Imaging and the many uses of Superparamagnetic Iron Oxide Nanoparticles (SPIONs) in Medicine”, and a group laboratory project exploring the effects of using air plasmas to alter the wettability of various polymer surfaces. <br/>

## Certifications
### Introduction to SQL and Data, Code First Girls, 04/2024 – 05/2024
Covers the fundamentals of SQL and database design (data manipulation and analysis in SQL, database manipulation and data visualisation using Tableau). By the end of the course, participants are able to build, deploy and maintain a database.
### Introduction to Python and Apps, Code First Girls, 08/2023 – 11/2023
Introduces the basics of Python (data types and variables, logic, loops and IF statements, using dictionaries and lists and finally introducing and using APIs). By the end of the course, participants are able to build a web app using an API.

## Projects
### Virtual Assistant
VANessa (Virtual Assistant for Neurodivergent Energy-Sensitive Scheduling Automation) is a custom-built intelligent scheduling system designed to integrate task management (_via_ Todoist) with calendar-based planning, tailored for cognitively complex workloads. Developed in Python and deployed _via_ Flask, VANessa automatically scores, prioritises, and schedules tasks using a weighted model incorporating urgency, importance, task duration and cognitive load. Rather than forcing users to conform to rigid productivity norms, VANessa flexes to accommodate working patterns, Spoon Theory-informed capacity, and changing environmental constraints providing real-time rescheduling using webhooks and tagging logic. Packages used: Unittest, Flask, re, Datetime

### Python With Training Wheels
This is an interactive Python plotting tool developed a full-stack web application to generate clean, reproducible Matplotlib/Seaborn plots from CSV uploads, designed for learners and analysts. The tool writes exportable Python code as users configure visualisations through a graphical user interface, supporting accessibility (_e.g.,_ colour-blind safe palettes), code quality (Black/Pylint-compliant), and transparent research workflows. Packages used: Flask, Werkzeug, Matplotlib, Seaborn

### American Sign Language Translator
This project uses the Sign Language MNIST data set, to build a convolutional neural network (CNN) to interpret live ASL into text. Plotted confusion matrix, Accuracy and Loss plots for both training and test sets. Current CNN has an 87.7% accuracy rate with its translation. Packages used: Pandas, NumPy, Matplotlib, Scikit-learn, Keras, ONNX.

## Teaching And Supervisory Experience #
<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<ul>{% for post in site.supervision reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Skills
### Technical Skills
**Analytical Techniques:** DLS, NMR (1H, 13C, DEPT-135), HPLC, Circular Dichroism, TEM, and displacement assays (Nile Red, Ethidium Bromide).  
**Method Development:** NTA, RMM for nanoparticle characterization; CFD simulations (coupled finite volume-discrete element method).  

### Software & Programming:
**Scientific Tools:** Python (Machine Learning: CNN, PCA), shell scripting and Make for automation. Git/GitHub for version control.  
**Data Analysis & Visualization:** Python (Matplotlib, Seaborn), Microsoft Office, Origin.  
**3D Design & Augmented Reality:** Blender, SolidWorks, [Unity](https://unity.com/), [Vuforia](https://www.ptc.com/en/products/vuforia) for scientific visualisation and dissemination of complex phenomena and AR-based data presentation.  

### Transferable Skills:
**Project Management:** Led a multidisciplinary research project integrating experimental, computational, and data-driven approaches, ensuring timely delivery of high-quality outputs.
**Teaching & Mentorship:** Supervised students, contributed to undergraduate teaching, and supported STEM outreach.
**Problem-Solving & Critical Thinking:** Troubleshot simulation issues, debugging, and experimental challenges to improve efficiency and reproducibility.
**Communication & Public Engagement:** Organised and participated in STEM outreach initiatives, including STEM Village Symposium and I'm a Scientist events.

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Prizes and Awards
### #RSC Poster, Online (via Twitter),	03/2020 ##
Runner-up in the Nanoscience category. One of 24 winners out of nearly 800 entries.

### RSC Organic Division North East Regional Meeting, Durham University,	03/2017 ##
Won Networking prize.

## Talks and Poster Presentations

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
 
## Outreach, Widening Participation and Public Engagement
### Sense about Science, Participant, 09/2022 ##
An interactive workshop on communicating with the media, designing effective public engagement and how early career researchers can influence science policy.

### The STEM Village, Organisation committee/session chair,  08/2020 
Organised a two-day virtual conference to showcase the work of a wide variety of LGBTQ+ researchers within STEM from across the globe. Particular emphasis was placed on showcasing LGBTQ+ POC researchers. <br/>
Approximately 700 viewers attended at least part of the talks included within the symposium. Learnt to use both open-source video editing software as well as YouTube Studio in order to add accurate captions to videos to enable accessibility of recorded talks for symposium participants. 

### I’m A Scientist (So stay at home!),	Participant,  05/2020 – 07/2020
Active participant in both Chemistry and Summer Zones. By the end of July, I had completed over 30 hours of webchats with a wide variety of groups aged 7 – 18. 

### West of Scotland Hub, STEM Ambassador, 01/2020 – 01/2023
STEM Ambassadors are PVG-checked volunteers who freely give up their time to bring science to life for a wide range of in and out of school groups. 

## Membership of Professional Societies
Royal Society of Chemistry (AMRSC) <br/>
British Society of Nanomedicine <br/>
UK and Ireland Controlled Release Society <br/>
Academy of Pharmaceutical Sciences <br/>


## Employment Experience #
### Graduate Teaching Assistant,	University of Strathclyde,	01/2020 – 08/2023
* Supervised computational and wet laboratory sessions for undergraduate Biomedical Scientists and Pharmacists <br/>

### Community Ambassador, Hello Student, 08/2020 – 01/2021
* Responsible for supporting residents and dealing with any incident that happened in the building outwith office hours 
* Problem solving and liaising with senior colleagues or external contractors when more specialist support was required to fix issues _e.g._ significant water leak in the building 

### Customer Contact Assistant, Public Sector Partnership Services Ltd, 01/2018 – 03/2018 and 01/2019 - 04/2019
* Taking phone calls and processing card and cheque payments for the payable garden waste service 
* Using computer systems to check information regarding household waste services.
* Developed an awareness of GDPR

### Graduate Teaching Assistant,	University of York, 01/2017 - 09/2017
* Delivered part of the undergraduate laboratory teaching, under the supervision of a senior demonstrator _e.g._ briefing undergraduates, making sure they work in a safe manner and providing assistance with new practical skills
* Responsible for marking laboratory work and providing written and verbal feedback <br/>

### General Operative, Various, 05/2012 - 09/2016
* A variety of  temporary roles including applying promotional stickers to packets and packing product in such a way to meet the requirements of the customer <br/>
<br/>
_References Available on Request_