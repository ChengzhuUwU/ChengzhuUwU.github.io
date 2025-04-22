---
title: "Untitled"
collection: publications
category: conferences
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about accelrating cloth and deformable body using heteronegeous computing'
date: 2025-5-31
venue: 'SIGGRAPH'
slidesurl: 
paperurl: 
bibtexurl: 
citation: 'Chengzhu He, Zhendong Wang, Zhaorui Meng, Junfeng Yao, Shihui Guo, Huamin Wang. (2025). <i>Preceding</i>.'
---
The key challenge of heterogeneous computing lies in task scheduling, which requires consideration of task dependencies and communication delays. Our work proposes a novel automatic task scheduling framework, in which simulation tasks such as collision detection and constraint iteration are modeled as directed-acyclic-graphs (DAGs). We also introduce an efficient scheduling method based on heterogeneous earliest completion time (HEFT) algorithm to minimize communication delays. In order to maximize the parallelism of non-linear Gauss Seidel iteration, we propose an innovative asynchronous iteration strategy that performs asynchronous data synchronization between devices to mask communication delays. In addition, we have designed task merging and prioritization strategies for asynchronous iterative tasks to achieve the best balance between convergence and parallelism. We have validated the effectiveness of our framework in various simulation methods, including XPBD, Vertex Block Descent, and Second Order Stencil Descent. Without reducing any computational tasks, we achieved a 350% improvement compared to pure CPU-implementation  and a 50% improvement compared to GPU-implementation on the Apple M3 chip (12 core CPU & 30 core GPU). The frame rate exceeds the sum of the frame rates in homogeneous environments, and this achievement may provide new ideas for large-scale and real-time simulations.
