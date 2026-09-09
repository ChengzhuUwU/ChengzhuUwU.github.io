---
title: "Automated Task Scheduling for Cloth and Deformable Body Simulations in Heterogeneous Computing Environments"
collection: publications
category: conferences
permalink: /publication/siggraph-2025-ats
excerpt: 'Accelerating cloth and deformable body simulation with automated task scheduling on heterogeneous CPU/GPU computing environments.'
date: 2025-5-31
venue: 'SIGGRAPH 2025 Conference Papers'
slidesurl: 'https://chengzhuuwu.github.io/files/ats_sig_slide.pptx'
paperurl: 'https://chengzhuuwu.github.io/files/ats_camera_ready.pdf'
bibtexurl: 'https://github.com/ChengzhuUwU/libAtsSim'
citation: 'Chengzhu He, Zhendong Wang, Zhaorui Meng, Junfeng Yao, Shihui Guo, Huamin Wang. <i>SIGGRAPH 2025 Conference Track</i>.'
layout: project
---

<p class="eyebrow">SIGGRAPH 2025 &nbsp; / &nbsp; Conference Papers</p>
<h1>Automated Task Scheduling for Cloth and Deformable Body Simulations in Heterogeneous Computing Environments</h1>
<p class="authors"><strong>Chengzhu He</strong>, Zhendong Wang, Zhaorui Meng, Junfeng Yao, Shihui Guo, Huamin Wang</p>
<div class="project-badges">
  <span class="venue">SIGGRAPH 2025</span>
  <div class="project-links">
    <a href="/files/ats_camera_ready.pdf">Paper <span aria-hidden="true">&#8599;</span></a>
    <a href="/files/ats_sig_slide.pptx">Slides <span aria-hidden="true">&#8599;</span></a>
    <a href="https://github.com/ChengzhuUwU/libAtsSim">Code <span aria-hidden="true">&#8599;</span></a>
  </div>
</div>

<figure>
  <img src="/publications/img_ats_overview.png" alt="Overview of the automated task scheduling framework" width="1266" height="638" decoding="async">
  <figcaption>Overview of the automated task scheduling framework for hybrid CPU/GPU simulation.</figcaption>
</figure>

<h2 id="abstract">Abstract</h2>
<p>The concept of the Internet of Things (IoT) has driven the development of system-on-a-chip (SoC) technology for embedded and mobile systems, which may define the future of next-generation computation. In SoC devices, efficient cloth and deformable body simulations require parallelized, heterogeneous computation across multiple processing units. The key challenge in heterogeneous computation lies in task distribution, which must account for varying inter-task dependencies and communication costs.</p>
<p>This paper proposes a novel framework for automated task scheduling to optimize simulation performance by minimizing communication overhead and aligning tasks with the specific strengths of each device. To achieve this, we introduce an efficient scheduling method based on the Heterogeneous Earliest Finish Time (HEFT) algorithm, adapted for hybrid systems. We model simulation tasks—such as those in iterative methods like Jacobi and Gauss-Seidel—as a Directed Acyclic Graph (DAG).</p>
<p>To maximize the parallelism of nonlinear Gauss-Seidel simulation tasks, we present an innovative asynchronous Gauss-Seidel method with specialized data synchronization across units. Additionally, we employ task merging and tailored task-sorting strategies for Gauss-Seidel tasks to achieve an optimal balance between convergence and efficiency.</p>
<p>We validate the effectiveness of our framework across various simulations, including XPBD, vertex block descent, and second-order stencil descent, using Apple M-series processors with both CPU and GPU cores. By maximizing computational efficiency and reducing processing times, our method achieves superior simulation frame rates compared to approaches that rely on individual devices in isolation.</p>

<h2 id="videos">Videos</h2>
<div class="embed">
  <iframe src="https://www.youtube.com/embed/tbRRSnt_j1g" title="Fast-forward video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="embed">
  <iframe src="https://www.youtube.com/embed/ZH2Jcpsg7J0" title="Pre-presentation video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<h2 id="source-code">Source Code</h2>
<p>The source code with hybrid Metal/C++ implementation is available on GitHub: <a href="https://github.com/ChengzhuUwU/libAtsSim">ChengzhuUwU/libAtsSim</a>.</p>

<h2 id="bibtex">BibTeX</h2>
<pre class="bibtex"><code>@inproceedings{he2025automated,
  title     = {Automated Task Scheduling for Cloth and Deformable Body Simulations in Heterogeneous Computing Environments},
  author    = {He, Chengzhu and Wang, Zhendong and Meng, Zhaorui and Yao, Junfeng and Guo, Shihui and Wang, Huamin},
  booktitle = {SIGGRAPH 2025 Conference Papers},
  year      = {2025}
}</code></pre>

<p class="back"><a href="/#research">&larr; Back to Research</a></p>
