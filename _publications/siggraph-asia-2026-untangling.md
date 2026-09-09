---
title: "Type-Free Global Intersection Analysis with Linear Displacement Fields"
collection: publications
category: conferences
permalink: /publication/siggraph-asia-2026-untangling/
excerpt: 'A type-free untangling framework that constructs separation responses directly from contour-anchored ray evidence rather than predefined contour categories, robustly resolving self-intersections in cloth and thin-shell simulation.'
date: 2026-12-01
venue: 'SIGGRAPH Asia 2026 Conference Papers'
slidesurl: ''
paperurl: 'https://chengzhuuwu.github.io/files/untangling_siggraph_asia_2026.pdf'
bibtexurl: 'https://github.com/ChengzhuUwU/Untangling26'
citation: 'Chengzhu He, Xudong Feng, Anjun Chen, Dan Song, Shihui Guo, Kui Wu. <i>SIGGRAPH Asia 2026 Conference Track</i>.'
layout: project
---

<p class="eyebrow">SIGGRAPH Asia 2026 &nbsp; / &nbsp; Conference Papers</p>
<h1>Type-Free Global Intersection Analysis with Linear Displacement Fields</h1>
<p class="authors"><strong>Chengzhu He</strong>, Xudong Feng, Anjun Chen, Dan Song, Shihui Guo, Kui Wu</p>
<div class="project-badges">
  <span class="venue">SIGGRAPH Asia 2026</span>
  <div class="project-links">
    <a href="/files/untangling_siggraph_asia_2026.pdf">Paper <span aria-hidden="true">&#8599;</span></a>
    <a href="/files/untangling_supplemental.pdf">Supplemental <span aria-hidden="true">&#8599;</span></a>
    <a href="https://youtu.be/cs_592tRAZQ">Video <span aria-hidden="true">&#8599;</span></a>
    <a href="https://github.com/ChengzhuUwU/Untangling26">Code <span aria-hidden="true">&#8599;</span></a>
  </div>
</div>

<figure>
  <img src="/publications/untangling_teaser.jpg" alt="Initial entangled states, initial ray hits, and resolved states for the corner-fold and cloth-drop benchmarks" width="3680" height="1926" decoding="async">
  <figcaption>Our self-intersection repair method resolves complex entanglements in thin-shell dynamics without topological classification — from folded cloth corners to a garment drop concentrating thousands of intersection contours.</figcaption>
</figure>

<h2 id="abstract">Abstract</h2>
<p>History-independent intersection repair is a critical bottleneck in physical simulation and geometric processing. Existing global intersection analysis (GIA) methods identify invalid regions of relatively small area, but they rely on type-specific heuristics for different contour categories, while local intersection contour minimization (ICM) methods are easier to deploy but often stall in local minima.</p>
<p>In this paper, we present a novel untangling framework that constructs separation responses directly from contour-anchored ray evidence rather than predefined contour categories. Our method uses intersection contours as anchors for the affected regions. For each intersection contour, we test a set of candidate linear displacement directions using conservative VF/EE/FV ray casting and filter the raw hits using cluster culling based on primitive adjacency, so that only hits belonging to the affected region survive. A contour merging strategy then resolves conflicts between solutions from different contours.</p>
<p>We evaluate our method on canonical contour configurations and extensive self-intersection benchmarks. Compared with GIA and ICM baselines, our method more consistently resolves intersections in challenging scenarios. The results show that our method is a practical, solver-compatible untangling pipeline for difficult cloth and thin-shell intersections.</p>

<h2 id="video">Video</h2>
<div class="embed">
  <iframe src="https://www.youtube.com/embed/cs_592tRAZQ" title="Supplemental video: Type-Free Global Intersection Analysis with Linear Displacement Fields" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<h2 id="code">Source Code</h2>
<p>The official implementation is available on GitHub: <a href="https://github.com/ChengzhuUwU/Untangling26">ChengzhuUwU/Untangling26</a>.</p>

<h2 id="bibtex">BibTeX</h2>
<pre class="bibtex"><code>@inproceedings{he2026typefree,
  title     = {Type-Free Global Intersection Analysis with Linear Displacement Fields},
  author    = {He, Chengzhu and Feng, Xudong and Chen, Anjun and Song, Dan and Guo, Shihui and Wu, Kui},
  booktitle = {SIGGRAPH Asia 2026 Conference Papers},
  year      = {2026}
}</code></pre>

<p class="back"><a href="/#research">&larr; Back to Research</a></p>
