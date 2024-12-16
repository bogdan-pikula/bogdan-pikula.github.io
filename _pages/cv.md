---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[View PDF](http://bogdan-pikula.github.io/files/CV_Dec_2024_ta.pdf)


Education
======
* Ph.D in Computer Science, **University of Toronto**, 2028 (expected)
* M.S. in Computer Science, **University of Toronto**, 2023
* B.S. in System Analysis, with Honors, **Taras Shevchenko National University of Kyiv**, 2021

Work experience
======
* Sep 2023 - Present: Research Assistant @ ***Dynamic Graphics Project***
  * Deployed and locally fine-tuned Image-Text-to-Text and Visual Question Answering (VQA) models, scaling them to handle interactive, user-centric tasks at real-time speeds. Integrated them into user interface demos.
  * Developed a human-AI collaborative system that uses LLMs to assist novice photographers in framing and enhancing image composition [preview](https://drive.google.com/file/d/1di0v8UHQn5MShDxBtT3nSdgwYIMjdMli/view?usp=sharing)
  * Supervisor: Dr. Daniel Wigdor

* Jan 2023 - Mar 2023: Research & Development Intern @ ***La Forge, Ubisoft Toronto***
  * Created a dataset of facial representations for different emotions and developed an approach for modeling realistic static facial expressions.
  * Helped implement seamless facial expression transition animation generation, tailoring them to different emotional contexts.
  * Collaborated on the development of an internal universal tool for visualizing facial expressions in Maya from muscle-skeleton facial representation.
  * Worked on a dynamic way to generate responsive facial reactions in gaming environments for more immersive character interactions.
  * Supervisor: Dr. Ylva Ferstl

* Sep 2022 - Aug 2023: Research Assistant @ ***University of Toronto & Bank of Canada Digital Analytic Zone***
  * Identifying emotional cues from video and audio sources.
  * Created a pipeline for extracting facial expressions, pose estimations, face and hand gestures from hundreds of hours of video data scaling parallelized compute on GPU clusters. Inference optimization performed.
  * Supervisor: Prof. Michelle Alexopoulos

* May 2022 - Aug 2022: Student Summer Researcher @ ***University of Toronto, Department of Computer Science***
  * Created a system for determining negative emotions in kids while using educational video games for studying math.
  * Created a tool for detecting shifts from the state of emotional neutrality to positivity/negativity based on facial attribute deviations, using the FACS coding system as the backbone.
  * Supervisors: Prof. Steve Engels (DCS) and Ana Zdravkovic (OISE)

* Sep 2021 - Aug 2022: Data Scientist @ ***Sierentz Global Merchants***
  * Lead a 3-person team tasked with automating data collection from public and private sources.
  * Automated acquisition, processing, and storing data on a PostgreSQL DB using AWS.
  * Analyzed the data and built statistical models for supply / demand forecasting, as well as other agricultural indicators.
  * Developed the back-end for a webtool used by Ags traders at Sierentz North America that improved access to historical and new data, its accuracy, and auditability.
  * Improved the process of calculating the logistics of connecting grain silos with major Ukrainian seaports by means of transport by rail network or by means of boats or trucks.
  * Supervisor: Andrea Massetti

  
Skills
======
* **Languages:** Python, C, CUDA, C++, SQL, js
* **Machine Learning:**
  * Deep Learning, 
  * Computer Vision, 
  * Time Series,
  * Facial Attribute Generation, 
  * Visualization, 
  * UI Understanding.
* **Frameworks:** PyTorch, TensorFlow, PyG, transformers, NumPy, Pandas, Sklearn, LightGBM, Matplotlib, JAX, ReactJS.
* **Tools:** Git, Databricks, WandB, Linux, Bash, LaTex, AWS, cuDNN, Gradio, Heroku.
* **Databases:** PostgreSQL, MongoDB, MySQL.

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
   -->

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* **[DGP Academy](https://www.dgp.toronto.edu/dgp-academy/). March 2024** 
A week-long outreach event hosted by DGP for high schoolers to get a glimpse of what research is like. Held a 3-day workshop on mesh simplification and computational fabrication.
* **[CSGSBS](https://www.cs.toronto.edu/csgsbs/about/). Sep 2022 - Dec 2024**
Helped organize events, delegated council meetings, and addressed students' concerns. Helped to establish a union office / lounge for graduate students.
* **[UofT summer research program for Ukrainians](https://www.utm.utoronto.ca/registrar/ukraine/). Feb 2023 - Apr 2023**
Interviewed candidates as an admission board member for the University of Toronto Summer Program for Students from Ukraine. The process included reviewing resumes and motivation letters, as well as conducting interviews to assess experience, technical strength, and research potential.