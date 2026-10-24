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
* Ph.D. in Structures, Mechanics & Construction Engineering, University of Waterloo, Sep 2024 – Present
  * Advisor: [Prof. Chul Min Yeum](https://cviss.net/)
  * Research: 3D Gaussian Splatting for scene reconstruction and understanding
* M.Eng. in Electronic and Information Engineering (Artificial Intelligence), University of Chinese Academy of Sciences, 2021 – 2024
  * Advisor: [Prof. Jianwei Guo](https://jianweiguo.net/)
  * Thesis: High-quality automatic texture reconstruction and intelligent generation for 3D digital content production
* B.S. in Computer Science, Yancheng Institute of Technology, 2011 – 2015

Research experience
======

* Sep 2024 – Present: Graduate Research Assistant, [CVISS Lab](https://cviss.net/), University of Waterloo
  * Learnable deformable kernels for 2D Gaussian Splatting (NeurIPS 2026)
  * Floater removal for 3D Gaussian Splatting with attention-based transformers
  * Interactive oriented bounding box extraction from 3D Gaussian Splatting

* Sep 2021 – Jun 2024: Graduate Research Assistant, Institute of Automation, Chinese Academy of Sciences
  * Texture reconstruction and diffusion-based texture generation for 3D assets
  * Neural rendering pipelines for 3D scene reconstruction (PyTorch, CUDA)

Work experience
======

* Nov 2023 – Aug 2024: Research Intern, AI Lab, [Well-Link Times](https://www.wl-times.com/)
  * Applied diffusion models to generate high-quality texture maps for 3D models, improving LPIPS and PSNR
  * Designed interactive tools addressing spatial consistency in 3D modeling workflows
  * Reduced game asset creation time from days to minutes through automated generation
  * Built an LLM-based prompt enhancement system for text-to-image generation

* Apr 2015 – Jul 2021: Algorithm Engineer, [Tingyun](https://www.tingyun.com/)
  * Built LSTM-based time-series forecasting of monthly active users for capacity planning
  * Designed an entropy-based URL aggregation algorithm, reducing storage requirements by 95%
  * Developed real-time anomaly detection for high-dimensional application performance metrics

Skills
======

* Programming & tools: Python, C++, JavaScript, Java, PyTorch, CUDA, Blender, Git, Docker, Linux
* Research areas: 3D computer vision, neural rendering, Gaussian Splatting, point cloud processing, 3D generative models

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
* Currently signed in to 43 different slack teams
* -->
