---
title: "Type-Free Global Intersection Analysis with Linear Displacement Fields"
collection: publications
category: conferences
permalink: /publication/siggraph-asia-2026-untangling
excerpt: 'A type-free untangling framework that constructs separation responses directly from contour-anchored ray evidence rather than predefined contour categories, robustly resolving self-intersections in cloth and thin-shell simulation.'
date: 2026-12-01
venue: 'SIGGRAPH Asia 2026 Conference Papers'
slidesurl: ''
paperurl: 'https://chengzhuuwu.github.io/files/untangling_siggraph_asia_2026.pdf'
bibtexurl: 'https://github.com/ChengzhuUwU/Untangling26'
citation: 'Chengzhu He, Xudong Feng, Anjun Chen, Dan Song, Shihui Guo, Kui Wu. <i>SIGGRAPH Asia 2026 Conference Track</i>.'
---

![Teaser: initial state, initial ray hits, and resolved state](untangling_teaser.jpg)

History-independent intersection repair is a critical bottleneck in physical simulation and geometric processing. Existing global intersection analysis (GIA) methods identify invalid regions of relatively small area, but they rely on type-specific heuristics for different contour categories, while local intersection contour minimization (ICM) methods are easier to deploy but often stall in local minima.

In this paper, we present a novel untangling framework that constructs separation responses directly from contour-anchored ray evidence rather than predefined contour categories. Our method uses intersection contours as anchors for the affected regions. For each intersection contour, we test a set of candidate linear displacement directions using conservative VF/EE/FV ray casting and filter the raw hits using cluster culling based on primitive adjacency, so that only hits belonging to the affected region survive. A contour merging strategy then resolves conflicts between solutions from different contours.

We evaluate our method on canonical contour configurations and extensive self-intersection benchmarks. Compared with GIA and ICM baselines, our method more consistently resolves intersections in challenging scenarios. The results show that our method is a practical, solver-compatible untangling pipeline for difficult cloth and thin-shell intersections.

**Authors:** Chengzhu He, Xudong Feng, Anjun Chen, Dan Song, Shihui Guo, Kui Wu

**Resources:** [Paper](https://chengzhuuwu.github.io/files/untangling_siggraph_asia_2026.pdf) | [Supplemental](https://chengzhuuwu.github.io/files/untangling_supplemental.pdf) | [Video](https://youtu.be/cs_592tRAZQ) | [Code](https://github.com/ChengzhuUwU/Untangling26)
