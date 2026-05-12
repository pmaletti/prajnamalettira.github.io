---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- This creates a nice, prominent download button -->
<!-- Download a compact version of my CV here: [📥 Download Resume](/files/Prajna_Malettira_s_Resume.pdf){: .btn style="background-color: #946e83; color: #000 !important; border: 2px solid #000; font-weight: 600; font-size: 0.9em; margin-bottom: 20px; text-decoration: none !important;"}
 -->
Download a compact version of my CV here: [<span style="font-size: 1.2em; line-height: 0; vertical-align: -2px; margin-right: 5px;">📄</span> Download Resume](/files/Prajna_Malettira_s_Resume.pdf){: .btn style="background-color: #946e83; color: #000 !important; border: 2px solid #000; font-weight: 600; font-size: 0.9em; padding: 6px 15px; border-radius: 50px; text-decoration: none !important; display: inline-flex; align-items: center; line-height: 1;"}
Education
======
* **Ph.D. in Electrical and Computer Engineering**, Purdue University (May, 2028)
* **B.Tech in Electronics and Communication Engineering**, PES University

Research Interests
======
<!-- * Efficient Large Language Models
* Neural Architecture Search
* Model Compression via Structured Pruning
* Generative Models
* Memorization in ML models
* Neuromorphic Computing -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 30px;">
  <span style="background-color: #ddf8e8; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #ddf8e8;">Efficient Large Language Models</span>
  <span style="background-color: #946e83; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #946e83;">Neural Architecture Search</span>
  <span style="background-color: #ddf8e8; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #ddf8e8;">Model Compression & Pruning</span>
  <span style="background-color: #946e83; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #946e83;">Generative Models</span>
  <span style="background-color: #ddf8e8; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #ddf8e8;">ML Memorization</span>
  <span style="background-color: #946e83; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #946e83;">Sparse Autoencoders & Dictionary Learning</span>
  <span style="background-color: #ddf8e8; color: #000; padding: 6px 15px; border-radius: 50px; font-weight: 600; font-size: 0.9em; border: 2px solid #ddf8e8;">Neuromorphic Computing</span>
</div>



Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<!-- <div class="compact-list">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</div>

<style>
  /* This targets the specific items in your publication list */
  .compact-list .list__item {
    margin-bottom: -15px; /* Pulls the next item up */
    padding-bottom: 0;     /* Removes extra bottom padding */
  }

  /* This ensures the titles don't have huge top margins */
  .compact-list .archive__item-title {
    margin-top: 5px; 
    margin-bottom: 0;
  }
</style> -->

Technical Skills
======
* **Languages & Tools:** Python · Bash · Git · MATLAB · Linux
* **Frameworks:** PyTorch, Hugging Face, Timm, Latex, OpenCV
* **Computing:** Distributed Training, SLURM, High-Performance Computing (HPC)

Work experience
======
**Graduate Research Assistant** | *Neuroelectronics Research Lab (NRL), Purdue University* (Aug 2023 - Present)
* *PI: Dr. Kaushik Roy*
* Driving research on Neural Architecture Search (NAS), Spiking Neural Networks (SNNs), and efficient Large Language Models (LLMs).
* Developing frameworks for structured pruning and latent space topology for data pruning, efficient and robust data coreset generation and data memorization pipelines.
* Leveraging Dictionary Learning and Sparse Autoencoders (SAEs) to bypass the expensive training-aware process of data attribution, memorization by developing novel techniques for data memorization.

**Graduate Teaching Assistant - EPICS** | *Purdue University* (Aug, 2023 - May, 2024)
* Guided undergraduate students through community-led engineering projects in the Greater Lafayette area, with a focus on fostering sustainability and practical design.

**Graduate Research Assistant** | *Integrated Imaging Lab (I2Lab), Purdue University* (May 2023 - Aug 2023)
* *PIs: Dr. Charles Bouman and Dr. Gregery Buzzard*
* Contributed to the development of Generative Plug-and-Play (GPnP), a novel method for posterior sampling in inverse problems.
* Implemented key image reconstruction algorithms (Expectation Maximization, PnP, Surrogate Functions, and Alternating Direction Method of Multipliers) in C.

**Project Intern** | *Collins Aerospace*, Bengaluru, India (Feb 2022 - May 2022)
* Built an Operations Framework for intelligent product segregation in the Cargo Systems department to ensure Just-in-Time process implementation.
* Automated in-progress work orders and managed inventory for critical spares, improving the tracking of maintenance and life-cycle ownership costs.

**Research and Development Intern** | *ABB*, Bengaluru, India (Sep 2021 - Dec 2021)
* Researched and developed predictive and condition-based maintenance models in Strategic Asset Management (SAM) using machine learning.
* Developed an algorithm using Pandas and Long Short-Term Memory (LSTM) neural networks to analyze time-series data for automated machine cycle logs.

Honors & Fellowships
======
* **SRC Research Scholar**, *Semiconductor Research Corporation (SRC)*
* **Millennium Fellow**, *Millennium Campus Network (MCN) & UN Academic Impact* (Aug 2021 - Nov 2021)
  * Implemented *Project Anzen: Your Friend in the Dark* to further the United Nations Sustainable Development Goals.