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
* Ph.D in Computer Engineering, North Carolina State University, Expected August 2025
* B.S. in Computer Engineering, North Carolina State University, August 2020
* B.S. in Electrical Engineering, North Carolina State University, August 2020

Research experience
======
* **Distinguished Graduate Researcher**  
  *Pacific Northwest National Laboratory and North Carolina State University, Raleigh, NC*  
  *August 2023 – Present*  
  - Designed a modular framework for graph neural networks (GNNs) in PyTorch to compress forward activations, achieving a 6–10x compression ratio with cuSZp on two PyG GNNs while retaining over 99% of the original accuracy.
  - Reduced the end-to-end time of extracting 45,612 feature sets for model training and inference from 180 days to 2 days by creating an end-to-end HPC workflow to accelerate a 3D tomogram refinement and extraction pipeline.
  - Enabled influence maximization approximation on a 7.5B edge US-scale network across 8,192 OLCF Frontier nodes by implementing opportunistic gathering, speculative execution, workload balancing, and memory footprint reduction.
  - Improved the performance of synchronous (135x) and asynchronous (75x) graph sampling approaches by developing a platform-agnostic parallel work fusing algorithm to reduce redundant memory behavior and increase concurrency.
  - Achieved a 60x average reduction in conflict graph construction time within Picasso, a memory-efficient iterative graph coloring algorithm, by designing a parallel streaming and domain-specific encoding approach for GPUs.

* **Ph.D. Intern**  
  *Pacific Northwest National Laboratory – Remote*  
  *May 2021 – August 2023*  
  - Evaluated a commercial high-level synthesis tool for two forms of graph sampling on a Xilinx Alveo U250 FPGA, comparing memory behavior and performance with CPU and GPU equivalents to identify improvement opportunities.
  - Accelerated greedy histogram counting up to 4.78x compared to CPU execution by architecting a resource-conscious FPGA dataflow pipeline using C++ high-level synthesis and offloading work from the CPU.

* **Graduate Research Assistant**  
  *North Carolina State University – Raleigh, NC*  
  *August 2020 – August 2023*  
  - Designed the hierarchical component of a parallel data structure for random forest classification, enabling the scheme to outperform cuML up to 2x in subsequent GPU evaluations.
  - Achieved up to a 4x speedup in OpenCL microbenchmarks on an Arria GX FPGA by implementing thread coarsening.

* **Undergraduate Research Assistant**  
  *North Carolina State University – Raleigh, NC*  
  *February 2019 – January 2020*  
  - Created a Python testbed to evaluate a sequence clustering algorithm for DNA-based storage.
  
Skills
======
* **Languages:** C++, Python, C
* **Parallel and Distributed Computing:** OpenCL, OpenMP, MPI, HIP (ROCm), CUDA
* **Frameworks and Libraries:** PyTorch, PyTorch Geometric, Xilinx Vitis HLS

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
  {% endfor %}</ul> -->
  
Honors and Awards
======
* Joint NC State University and Pacific Northwest National Laboratory Distinguished Graduate Research Program, 2023
* North Carolina State University Provost’s Doctoral Fellowship, 2020
* North Carolina State University College of Engineering Graduate Merit Award, 2020
* Toni Christine Masini Memorial Marching Band Scholarship, 2019
* Eagle Scout, 2016
