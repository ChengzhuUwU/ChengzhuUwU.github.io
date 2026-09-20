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
<p>History-independent intersection repair is a critical bottleneck in physical simulation and geometric processing. Existing global intersection analysis (GIA) methods identify invalid regions of relatively small area, but they rely on type-specific heuristics for different contour categories, while local intersection contour minimization (ICM) methods are simpler to deploy but often stall in local minima under deep or nested penetrations.</p>
<p>In this paper, we present a novel untangling framework that formulates intersection resolution as a minimum-displacement separation-direction problem. For each intersection contour, we test a set of candidate linear displacement directions using VF/EE/FV ray casting and filter the raw hits using cluster culling based on primitive adjacency to find the valid hits belonging to the penetration region. We rank candidate directions by displacement cost, and refine the most promising direction with projected Newton updates on the sphere. Finally, we convert the valid hit support into standard proximity-style penalty pairs and integrate them into the standard physics simulator.</p>
<p>We evaluate our method on diverse contour configurations and self-intersection benchmarks. Compared with the GIA and ICM baselines, our method resolves intersections more consistently, particularly in challenging cases involving deep and nested layers. The results show that our method is a practical, solver-compatible untangling pipeline for complex mesh intersections.</p>

<h2 id="video">Video</h2>
<div class="embed">
  <iframe src="https://www.youtube.com/embed/cs_592tRAZQ" title="Supplemental video: Type-Free Global Intersection Analysis with Linear Displacement Fields" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<h2 id="code">Source Code</h2>
<p>The official implementation is available on GitHub: <a href="https://github.com/ChengzhuUwU/Untangling26">ChengzhuUwU/Untangling26</a>.</p>

<h2 id="bibtex">BibTeX</h2>
<pre class="bibtex"><code>@article{he2025untanglingrc,
  title={Type-Free Global Intersection Analysis with Linear Displacement Fields},
  author={He, Chengzhu and Feng, Xudong and Chen, Anjun and Song, Dan and Guo, Shihui and Wu, Kui},
  journal={ACM Transactions on Graphics},
  volume={45},
  number={6},
  pages={1--17},
  year={2026},
  publisher={ACM New York, NY}
}</code></pre>

<p class="back"><a href="/#research">&larr; Back to Research</a></p>

