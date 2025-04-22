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
* M.S. in Computer Science and Technology, GitHub University, 2023
* B.S. in Digital Media Technology, Xiamen University, 2019


Work experience
======
* Summer 2025: Algorithm Intern (expected)
  * miHoYo

* Winter 2024: Algorithm Intern
  * Style3D Research
  * Duties included: Research for heterogenenous computing
  
* Summer 2023: Algorithm Intern
  * Style3D Research
  * Duties included: Developing GPU-based cloth simulation mudule for MacOS.

* Winter 2022: Algorithm Intern
  * Xinyu Technology, Beijing
  * Duties included: Developing GPU-based cloth simulator on Unity.
  
Skills
======
* **Integration Methods**: Newton Method, XPBD, VBD, SOSD, Explicit integration
* **Numerical Computation**: PCG, Multigrid, Demain-decomposition, Preconditioning, Gradient Descent
* **Collision Detection/Response**: Spatial Hashing/LBVH/Descrete Proximity/Impact Zone/IPC
* **Energy**: StVK/Stable Neohookean/ARAP, Quadratic bending, Dehidral-Angle bending, Mass-spring, IPC barrier energy (with their semi-positive-define hessian)
* **High-performance Computing**: C++ multi-thread, GPU architecture, low-level optimization (e.g. shared-memory/warp intrinsic/reduce/scan/sorting)
* **Coding**: C++/Cmake, CUDA/Metal/Unity Compute Shader, Matlab, Python, C#, go, git
* **Rendering**: OpenGL, Blender script


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
