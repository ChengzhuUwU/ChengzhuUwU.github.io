---
title: "LibAtsSim"
collection: publications
category: projects
permalink: /publication/open-source-proj-libatssim
excerpt: 'Code for SIGGRAPH 2025 conference paper: Automated Task Scheduling for Cloth and Deformable Simulation on Heterogeneous Environments'
date: 2025-5-31
venue: 'Github'
bibtexurl: 'https://github.com/ChengzhuUwU/libAtsSim'
citation: 'https://github.com/ChengzhuUwU/libAtsSim'
layout: project
---

<p class="eyebrow">Open Source &nbsp; / &nbsp; Heterogeneous Simulation Engine</p>
<h1>LibAtsSim</h1>
<div class="project-badges">
  <span class="venue review">Open Source</span>
  <div class="project-links">
    <a href="https://github.com/ChengzhuUwU/libAtsSim">GitHub <span aria-hidden="true">&#8599;</span></a>
  </div>
</div>

<figure>
  <img src="/publications/example3_iter_12_schedule.png" alt="Task schedule of the asynchronous iteration across devices" width="5369" height="1013" decoding="async">
  <figcaption>Task schedule of the asynchronous Gauss-Seidel iteration across CPU and GPU units.</figcaption>
</figure>

<h2 id="about">About</h2>
<p>LibAtsSim is the official C++/Metal implementation of the SIGGRAPH 2025 conference paper <a href="/publication/siggraph-2025-ats/">"Automated Task Scheduling for Cloth and Deformable Body Simulations in Heterogeneous Computing Environments"</a>.</p>
<p>Authors: Chengzhu He, Zhendong Wang, Zhaorui Meng, Junfeng Yao, Shihui Guo, Huamin Wang.</p>
<p>We provide several examples to show our scheduler and the progress of asynchronous iterations. Comparison of asynchronous and synchronous results:</p>
<p><img src="/publications/example2_simulation_async.png" alt="Asynchronous result" decoding="async"> <img src="/publications/example2_simulation_sync.png" alt="Synchronous result" decoding="async"></p>

<p class="back"><a href="/#research">&larr; Back to Research</a></p>
