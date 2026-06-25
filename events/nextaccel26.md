---
layout: nextaccel26
title: nextaccel26
permalink: /events/nextaccel26
---


#### [Introduction](#Intro) | [Topics](#topics) | [Dates](#dates) | [Organizers](#org) | [Program Committee](#pc) | [Submission](#submission) | [Program](#program) 
----

#### held in conjunction with [ICS'26](https://dipsa-qub.github.io/ICS2026-webpage/) and in cooperation with [ACM](https://www.acm.org/)
#### 2:00PM - 5:30PM, July 06, 2026
#### Meeting room 7, [Assembly Buildings Conference Centre](https://dipsa-qub.github.io/ICS2026-webpage/attending/venue.html)
---

### <a name="program"></a> Keynote: Memory-Centric Computing: Enabling Fundamentally Efficient & Intelligent Machines
#### Speaker: Professor Onur Mutlu (ETH Zürich, Switzerland)

##### Bio:
Onur Mutlu is a Professor of Computer Science at ETH Zurich. He previously held the William D. and Nancy W. Strecker Early Career Professorship at Carnegie Mellon University. His research interests are in computer architecture, computing systems, hardware security, memory & storage systems, and bioinformatics, with a major focus on designing fundamentally energy-efficient, high-performance, and robust computing systems. Many techniques he, with his group and collaborators, has invented over the years have largely influenced industry and have been employed in commercial microprocessors and memory & storage systems used daily by billions of people. He obtained his PhD and MS in ECE from the University of Texas at Austin and BS degrees in Computer Engineering and Psychology from the University of Michigan, Ann Arbor. He started the Computer Architecture Group at Microsoft Research (2006-2009), and held product, research and visiting positions at Intel Corporation, Advanced Micro Devices, VMware, Google, and Stanford University. He received various honors for his impactful research, including the 2025 IEEE Computer Society Harry H. Goode Memorial Award “for seminal contributions to computer architecture research and practice, especially in memory systems,” 2024 IFIP Jean-Claude Laprie Award in Dependable Computing (for the original RowHammer work), 2021 IEEE High Performance Computer Architecture Conference Test of Time Award (for the Runahead Execution work), 2022 Persistent Impact Prize of the Non-Volatile Memory Systems Workshop (for the original architectural work on Phase Change Memory), 2025 IEEE/IFIP International Conference on Dependable Systems and Networks Test-of-Time Award (for the AVATAR work), 2023 Huawei OlympusMons Award in Storage Systems, 2021 Intel Outstanding Researcher Award, 2019 ACM SIGARCH Maurice Wilkes Award, and dozens of best paper, “Top Pick” paper, and Best Artifact recognitions at various leading computer systems, architecture, and security venues. He is an AAAS Fellow, ACM Fellow, IEEE Fellow, and an elected member of the Academy of Europe. He enjoys teaching, mentoring, and enabling & democratizing access to high-quality research and education. He has supervised 27 PhD graduates, many of whom received major dissertation & other awards, more than 20 postdoctoral trainees, and more than 70 Master’s and Bachelor’s students. His computer architecture and digital logic design course lectures and materials are freely available on YouTube (https://www.youtube.com/OnurMutluLectures & https://www.youtube.com/@CMUCompArch), and his research group (https://safari.ethz.ch/) makes a wide variety of open-source artifacts freely available online (https://github.com/CMU-SAFARI). For more information, please see his webpage at https://people.inf.ethz.ch/omutlu/.

##### Abstract:
Computing is bottlenecked by data. Large amounts of application data overwhelm the storage capability, communication capability, and computation capability of the modern machines we design today. As a result, many key applications' performance, efficiency, and scalability are bottlenecked by data movement. In this talk, we describe three major shortcomings of modern computers in terms of 1) dealing with data, 2) taking advantage of vast amounts of data, and 3) exploiting different semantic properties of application data. We argue that an intelligent computing architecture should be designed to handle data well. We posit that handling data well requires designing architectures based on three key principles: 1) data-centric, 2) data-driven, 3) data-aware. We give examples of how to exploit these principles to design a much more efficient and higher performance computing system. We especially discuss recent research that aims to fundamentally reduce memory latency and energy, and practically enable computation close to data, with at least two promising directions: 1) processing using memory, which exploits the fundamental operational properties of memory chips to perform massively-parallel computation in memory, with low-cost changes, 2) processing near memory, which integrates sophisticated additional processing capability in memory chips, the logic layer of 3D-stacked technologies, or memory controllers to enable near-memory computation with high memory bandwidth and low memory latency. We show both types of architectures can enable order(s) of magnitude improvements in performance and energy consumption of many important workloads, such as artificial intelligence, machine learning, graph analytics, database systems, video processing, climate modeling, genome analysis. We discuss how to enable adoption of such fundamentally more intelligent architectures, which are key to efficiency, performance, and sustainability. We conclude with some research opportunities in and guiding principles for future computing architecture and system designs.

An accompanying overview of modern memory-centric computing ideas & systems can be found at https://arxiv.org/pdf/2012.03112 ("A Modern Primer on Processing in Memory", updated February 2025). A shorter invited paper from IMW 2025 is at https://arxiv.org/pdf/2505.00458 (“Memory-Centric Computing: Solving Computing’s Memory Problem”, May 2025)

----

### Invited Talk: Abstract Chemical Programs to Concrete Chemical Accelerators
#### Speaker: Dr. Antonino Tumeo (Chief Computer Scientist, Pacific Northwest National Laboratory, USA)
##### Abstract:
Chemical reaction networks (CRNs) offer a radically different substrate for energy-efficient scientific computing, with the potential to execute nonlinear dynamical computations directly in chemistry rather than emulating them on conventional digital hardware. However, a major obstacle remains between the compiler view of chemical computing and a physically meaningful implementation: compiler-generated CRNs are abstract, using symbolic species and idealized reactions, while real chemical systems are constrained by available biochemical reaction motifs, stoichiometry, kinetics, and shared species consistency.

This talk presents CRN2DB, a new matching capability in the ChemComp compilation flow that bridges this gap. CRN2DB takes abstract CRNs produced from ordinary differential equation specifications and systematically instantiates them with concrete reactions drawn from biochemical databases such as ModelSEED. The central challenge is that reactions cannot be matched independently: when multiple abstract reactions share a species, their concrete assignments must remain globally consistent. We formulate this as a constrained weighted assignment problem and solve it using a frontier-based dynamic programming algorithm over the species-sharing hypergraph of the compiled CRN. By exploiting the low-treewidth structure typical of compiler-generated CRNs, and combining stoichiometric indexing with AC-3 pruning, the approach makes exact matching practical even against databases containing tens of thousands of reactions.

Beyond the algorithmic contribution, CRN2DB illustrates the kind of cross-layer software support required for emerging non-digital accelerators. It turns chemical computing from an abstract model into a compilable target with explicit links to real biochemical substrates, while preserving hooks for future thermodynamic, kinetic, and uncertainty-aware scoring. The result is a concrete step toward programmable chemical accelerators for post-Moore, energy-constrained HPC workflows.

----

### Invited Talk: HDCU -- A Configurable, General-Purpose RISC-V Accelerator for Hyperdimensional Computing
#### Speaker: Marco Angioli (Sapienza Università di Roma, Italy)
##### Abstract:
Hyperdimensional Computing (HDC) is a neuro-inspired computing paradigm that represents information using high-dimensional distributed representations, which are combined and compared through simple vector arithmetic. This principle endows HDC with several attractive properties, including robustness, scalability, and inherent parallelism, that make it well-suited for learning tasks on resource-constrained edge devices and a natural candidate for hardware acceleration. Most HDC accelerators in the literature, however, rely on fixed design choices tailored to a specific task, dataset, and hypervector size, lacking the flexibility to adapt across different contexts. This talk introduces HDCU, a reconfigurable hardware accelerator powered by a novel RISC-V instruction set extension. HDCU accelerates core arithmetic operations on hypervectors and can be configured at synthesis time to balance execution speed and resource usage, adapting to diverse applications. A custom RISC-V Instruction Set Extension is designed to efficiently control the accelerator, with instructions fully integrated into the GCC compiler chain and exposed to the programmer as intrinsic function calls. The dual flexibility coming from hardware configuration and software programmability sets this work apart from application-specific solutions in the literature, offering a unique, versatile accelerator adaptable to a wide range of applications and learning tasks.

----

### Invited Talk: Spiker: open FPGA-powered neuromorphic computing acceleration with local learning at the edge
#### Speaker: Stefano Di Carlo (Politecnico di Torino, Italy)

----

### Regular Paper: The RISC-V VecR extension: Adding internal registers to RVV
#### Speaker: Mariusz Szczepaniak (The University of Glasgow, Scotland)

----

### Regular Paper: Post-Moore Technologies for Plasma Simulation: A Community Roadmap
#### Speaker: Luca Pennati (KTH, Sweden)

----

### Short Paper: An Energy Characterization Study of ML operators in XNNPACK on RISC-V Vector Hardware
#### Speaker: Ruimin Shi (KTH, Sweden)

----
### <a name="Intro"></a>Introduction
As the scaling limits of traditional general-purpose processors become increasingly apparent, heterogeneous computing has emerged as  a central paradigm for sustaining performance growth, improving energy efficiency, and enabling new classes of computation in the post-Moore era. Modern and future computing systems are rapidly evolving toward extreme heterogeneity, integrating a diverse set of accelerators and execution substrates, ranging from **AI accelerators, neuromorphic and analog computing devices, near- and in-memory accelerators, RISC-V custom processors, CGRAs, to emerging quantum processing units (QPUs)**. 

This architectural diversity enables extreme specialization, allowing algorithms to be mapped onto the most suitable hardware substrates, thereby reducing data movement, improving performance-per-watt, and enabling scalable parallelism across a wide spectrum of workloads. These systems are already reshaping domains such as machine learning, data analytics, scientific simulation, and real-time decision making. At the same time, they introduce profound challenges in programmability, performance portability, system software, and end-to-end co-design. This workshop aims to provide a focused forum to examine the rapidly expanding design space of heterogeneous computing and the opportunities it offers for future high-performance and sustainable systems. 

By bringing together researchers and practitioners spanning applications, algorithms, programming systems, middleware, and hardware platforms, NextAccel seeks to promote cross-layer interaction and informed exchange across traditionally siloed communities. The workshop will serve as a venue for critically assessing the current state-of-the-art, distilling key architectural and software challenges, and identifying realistic technology paths and co-design approaches that can shape the next generation of accelerator-rich computing systems. 

### <a name="topics"></a>Topics of Interest 
The topics of interest include, but are not limited to:

+ Design experiences and best practices with novel accelerators, including AI accelerators, neuromorphic computing devices, analog computing devices, RISC-V accelerators, CGRAs, in/near-memory acceleration, and QPUS

+ Software stack, middleware, and system infrastructure

+ Energy optimization, power efficiency, and sustainability studies

+ Profiling, Performance analysis, and Benchmarking

+ Algorithm-hardware and system co-design methodologies

+ Use cases and applications studies

+ Programming models, programmability and performance portability

----

### <a name="pc"></a>Program Committee
+ Dimitrios Soudris, National Technical University of Athens, Greece
+ Suma George Cardwell, Sandia National Laboratories, USA
+ Nick Brown, EPCC - The University of Edinburgh, UK
+ Anup Das, Drexel University, USA
+ John Leidel, Tactical Computing Laboratories, USA
+ Catherine Schuman, the University of Tennessee, USA
+ Anastasiia Butko, Lawrence Berkeley National Laboratory, USA
+ Katarzyna Swirydowicz, AMD, USA
+ Filippo Mantovani, Barcelona Supercomputing Center, Spain
+ Ivy Peng, KTH Royal Institute of Technology, Sweden

---
### <a name="org"></a>Organizers
 + Antonino Tumeo (Pacific Northwest National Laboratory, USA)
 + Jeffrey Vetter (Oak Ridge National Laboratory, USA)
 + Stefano Markidis (KTH Royal Institute of Technology, Sweden)

----

### <a name="dates"></a>Important Dates
 + Submission Deadline -- ~~April 15~~,April 20, 2026 (AoE) -- [Submission is Open](https://easychair.org/conferences/?conf=nextaccel26). 
 + Notifications -- May 01, 2026 (AoE)
 + Workshop -- July 06, 2026

---

### <a name="submission"></a>Submission and Review Process
[Submission is Open](https://easychair.org/conferences/?conf=nextaccel26). Submissions must use the ACM template at https://www.acm.org/publications/proceedings-template (use \documentclass[sigconf,screen,final]{acmart} in the ACM LaTeX template). Submitted manuscripts may not exceed eight (8) pages in length for regular papers and at least (4) pages for short papers, excluding references. Submitted papers must represent original unpublished research that is not currently under review for any other conference or journal. Papers will be evaluated based on novelty, technical soundness, clarity of presentation, and impact. 

Accepted papers can be included in the ACM proceedings. ACM is transitioning in 2026 to 100% Open Access. Full/short papers require the open access fee unless corresponding authors are from participating institutions at https://libraries.acm.org/acmopen/open-participants. For more details, please visit https://www.acm.org/publications/openaccess






