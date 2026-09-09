---
permalink: /
title: ""
layout: home
author_profile: false
description: "Chengzhu He is a Ph.D. student at Xiamen University working on physics-based simulation, heterogeneous computing, and rendering."
redirect_from: 
  - /about/
  - /about.html
---

<section id="about" class="intro" aria-labelledby="name">
  <div class="intro-copy">
    <p class="eyebrow">Ph.D. Student &nbsp; / &nbsp; Xiamen University</p>
    <h1 id="name">Chengzhu He <span lang="zh-Hans">(何成竹)</span></h1>
    <p>I am a Ph.D. student at <a href="https://www.xmu.edu.cn/">Xiamen University</a>, advised by Prof. <a href="https://informatics.xmu.edu.cn/info/1018/43139.htm">Shihui Guo</a> (welcome to visit our lab: <a href="https://www.humanplus.xyz/">HumanPlus</a>).</p>
    <p>My research centers on forward <strong>physics-based simulation</strong> for computer graphics, mainly cloth and deformable-body simulation, together with high-performance computing, heterogeneous computing, and rendering.</p>
    <p>Recently, I have also become interested in embodied intelligence and robotics.</p>
    <p>I am always happy to chat about simulation, graphics, and systems, so feel free to contact me at any time. If you are interested in collaborating, you can also reach my supervisors, Prof. Shihui Guo and Dr. Anjun Chen, through <a href="https://www.humanplus.xyz/team">HumanPlus</a>.</p>
    <p class="contact">Email: <a href="mailto:chengzhuhe@stu.xmu.edu.cn">chengzhuhe@stu.xmu.edu.cn</a> &nbsp;&middot;&nbsp; WeChat: huohuohuazi</p>
    <div class="profile-links" aria-label="Profiles and contact">
      <a href="https://github.com/ChengzhuUwU">GitHub <span aria-hidden="true">&#8599;</span></a>
      <a href="https://www.zhihu.com/people/tian-fen-fen-29">Zhihu <span aria-hidden="true">&#8599;</span></a>
      <a href="https://qm.qq.com/q/TtBqiKBya">QQ <span aria-hidden="true">&#8599;</span></a>
      <a href="https://www.humanplus.xyz/">HumanPlus Lab <span aria-hidden="true">&#8599;</span></a>
    </div>
  </div>
  <figure class="portrait">
    <img src="/images/me.png" alt="Portrait of Chengzhu He" width="777" height="1146" fetchpriority="high">
    <figcaption><span class="location-dot" aria-hidden="true"></span>Xiamen, Fujian, China</figcaption>
  </figure>
</section>

<section id="research" class="section" aria-labelledby="research-title">
  <div class="section-heading"><h2 id="research-title">Research</h2><span class="section-note">Publications &amp; open-source work</span></div>
  <p class="research-note">Robust and fast cloth &amp; deformable-body simulation — intersection repair, task scheduling, and heterogeneous GPU systems.</p>
  <div class="papers">
    <article class="paper">
      <a class="paper-teaser" href="/publications/untangling_teaser.jpg" target="_blank" rel="noopener" aria-label="View untangling teaser at full size (opens in a new tab)"><img src="/publications/untangling_teaser.jpg" alt="Teaser: initial entangled states, initial ray hits, and resolved states for cloth benchmarks" width="3680" height="1926" loading="lazy" decoding="async"><span aria-hidden="true">View image &#8599;</span></a>
      <div class="paper-body">
        <div class="paper-label"><span class="venue">SIGGRAPH Asia 2026</span><span class="paper-topic">Untangling &amp; intersection repair</span></div>
        <h3><a href="/publication/siggraph-asia-2026-untangling/">Type-Free Global Intersection Analysis with Linear Displacement Fields</a></h3>
        <p class="authors"><strong>Chengzhu He</strong>, Xudong Feng, Anjun Chen, Dan Song, Shihui Guo, Kui Wu</p>
        <p class="abstract">A type-free untangling framework that resolves self-intersections in cloth and thin-shell simulation without collision history or contour classification. It tests candidate linear displacement directions with conservative VF/EE/FV ray casting, culls spurious hits by adjacency-based clustering, and refines separation directions directly from contour-anchored evidence, consistently outperforming GIA and ICM baselines in challenging scenarios.</p>
        <div class="paper-links"><a href="/files/untangling_siggraph_asia_2026.pdf">Paper <span aria-hidden="true">&#8599;</span></a><a href="/files/untangling_supplemental.pdf">Supplemental <span aria-hidden="true">&#8599;</span></a><a href="https://youtu.be/cs_592tRAZQ">Video <span aria-hidden="true">&#8599;</span></a><a href="https://github.com/ChengzhuUwU/Untangling26">Code <span aria-hidden="true">&#8599;</span></a></div>
      </div>
    </article>
    <article class="paper">
      <a class="paper-teaser" href="/publications/img_ats_overview.png" target="_blank" rel="noopener" aria-label="View ATS overview figure at full size (opens in a new tab)"><img src="/publications/img_ats_overview.png" alt="Overview of the automated task scheduling framework" width="1266" height="638" loading="lazy" decoding="async"><span aria-hidden="true">View image &#8599;</span></a>
      <div class="paper-body">
        <div class="paper-label"><span class="venue">SIGGRAPH 2025</span><span class="paper-topic">Cloth &amp; deformable-body simulation</span></div>
        <h3><a href="/publication/siggraph-2025-ats/">Automated Task Scheduling for Cloth and Deformable Body Simulations in Heterogeneous Computing Environments</a></h3>
        <p class="authors"><strong>Chengzhu He</strong>, Zhendong Wang, Zhaorui Meng, Junfeng Yao, Shihui Guo, Huamin Wang</p>
        <p class="abstract">An automated task-scheduling framework that accelerates cloth and deformable-body simulations across heterogeneous CPU/GPU systems. It adapts the HEFT algorithm to hybrid devices and introduces an asynchronous Gauss-Seidel method with specialized data synchronization to maximize parallelism on Apple M-series processors.</p>
        <div class="paper-links"><a href="/files/ats_camera_ready.pdf">Paper <span aria-hidden="true">&#8599;</span></a><a href="/files/ats_sig_slide.pptx">Slides <span aria-hidden="true">&#8599;</span></a><a href="https://github.com/ChengzhuUwU/libAtsSim">Code <span aria-hidden="true">&#8599;</span></a></div>
      </div>
    </article>
    <article class="paper">
      <a class="paper-teaser" href="/publications/example3_iter_12_schedule.png" target="_blank" rel="noopener" aria-label="View task schedule figure at full size (opens in a new tab)"><img src="/publications/example3_iter_12_schedule.png" alt="Task schedule of the asynchronous iteration across devices" width="5369" height="1013" loading="lazy" decoding="async"><span aria-hidden="true">View image &#8599;</span></a>
      <div class="paper-body">
        <div class="paper-label"><span class="venue review">Open Source</span><span class="paper-topic">Heterogeneous simulation engine</span></div>
        <h3><a href="https://github.com/ChengzhuUwU/libAtsSim">LibAtsSim</a></h3>
        <p class="abstract">The C++/Metal implementation of our SIGGRAPH 2025 paper, with examples showing the task scheduler and the progress of asynchronous Gauss-Seidel iterations across CPU and GPU units.</p>
        <div class="paper-links"><a href="https://github.com/ChengzhuUwU/libAtsSim">GitHub <span aria-hidden="true">&#8599;</span></a></div>
      </div>
    </article>
    <article class="paper">
      <a class="paper-teaser" href="/publications/RotationCylinder60s.gif" target="_blank" rel="noopener" aria-label="View cloth rotation simulation clip (opens in a new tab)"><img src="/publications/RotationCylinder60s.gif" alt="Cloth simulation of a rotating cylinder" width="400" height="225" loading="lazy" decoding="async"><span aria-hidden="true">View image &#8599;</span></a>
      <div class="paper-body">
        <div class="paper-label"><span class="venue review">Open Source</span><span class="paper-topic">GPU physics simulation</span></div>
        <h3><a href="https://github.com/ChengzhuUwU/LuisaComputeSimulator">LuisaComputeSimulator</a></h3>
        <p class="abstract">A high-performance, cross-platform physics simulator built on LuisaCompute, supporting cloth and rigid-body simulation with penetration-free contact handling, accelerated by CUDA, DirectX 12, Vulkan, Metal, and fallback CPU backends.</p>
        <div class="paper-links"><a href="https://github.com/ChengzhuUwU/LuisaComputeSimulator">GitHub <span aria-hidden="true">&#8599;</span></a></div>
      </div>
    </article>
  </div>
</section>

<section id="experience" class="section" aria-labelledby="experience-title">
  <div class="section-heading"><h2 id="experience-title">Internships</h2><span class="section-note">Industry research experience</span></div>
  <div class="timeline-item">
    <p class="dates">Jun 2025 &ndash; Sep 2025</p>
    <div><h3>miHoYo</h3><p class="role">Graphics Pre-Research Intern</p><p>Shanghai, China</p></div>
  </div>
  <div class="timeline-item">
    <p class="dates">Oct 2024 &ndash; Jan 2025</p>
    <div><h3>Style3D Research</h3><p class="role">Academic Research Intern</p><p>Hangzhou, China</p></div>
  </div>
  <div class="timeline-item">
    <p class="dates">May 2023 &ndash; Sep 2023</p>
    <div><h3>Style3D Research</h3><p class="role">Simulation Engine Intern</p><p>Hangzhou, China</p></div>
  </div>
  <div class="timeline-item">
    <p class="dates">Oct 2022 &ndash; Feb 2023</p>
    <div><h3>Xinyu Technology</h3><p class="role">Simulation Engine Intern</p><p>Beijing, China</p></div>
  </div>
</section>

<section id="education" class="section" aria-labelledby="education-title">
  <div class="section-heading"><h2 id="education-title">Education</h2><span class="section-note">All at Xiamen University</span></div>
  <div class="timeline-item">
    <p class="dates">2025 &ndash; Present</p>
    <div><h3>Xiamen University</h3><p class="role">Ph.D. Student</p><p>Advisor: Prof. <a href="https://informatics.xmu.edu.cn/info/1018/43139.htm">Shihui Guo</a></p><p class="detail">Transferred from the master's program to the Ph.D. program in 2025.</p></div>
  </div>
  <div class="timeline-item">
    <p class="dates">2023 &ndash; 2025</p>
    <div><h3>Xiamen University</h3><p class="role">Master's Student</p><p>Fujian, China</p></div>
  </div>
  <div class="timeline-item">
    <p class="dates">2019 &ndash; 2023</p>
    <div><h3>Xiamen University</h3><p class="role">Undergraduate Student</p><p>Fujian, China</p></div>
  </div>
</section>
