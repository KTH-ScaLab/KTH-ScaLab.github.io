---
layout: memo24
title: memo24
permalink: /events/memo24
---


#### [Introduction](#Intro) | [Topics](#topics) | [Dates](#dates) | [Organizers](#org) | [Program Committee](#pc) | [Submission](#submission) | [Program](#program) 
----

#### held in conjunction SC24: [The International Conference on High Performance Computing, Networking, Storage and Analysis](https://sc24.supercomputing.org/) and in cooperation with [IEEE Computer Society](https://www.computer.org)
#### Time/Date: 2:00PM - 5:30PM, Sunday, November 17, 2024
#### Location: Room 302, [the Georgia World Congress Center, Atlanta](https://sc24.supercomputing.org/attend/convention-center/)
---

## <a name="program"></a>Program (2:00PM - 5:30PM, Room 302, Sunday, November 17, 2024)

### 2:00-2:45pm: Invited Talk: Memory & Storage: The Power of HPC/AI
Speaker: Dr. Jongryool Kim (SK Hynix)

Abstract: The growth of AI/Deep learning and data analytics has created many of the most challenging HPC workloads in recent years. Usually HPC/AI applications are driving the need for better memory and storage performance and capacity and despite significant advancements, memory and storage in HPC/AI still encounters several challenges in these. SK hynix has tried to continuous innovation and technological breakthroughs to solve these challenges in Memory/Storage.
As part of these efforts, this talk will highlight the key roles that advanced memory and storage play in HPC/AI ecosystem and potential benefits of “Processing Near Data with CXL/HBM/SSD” and “CXL Pooled Memory's Data Sharing” for HPC/AI Systems.

Bio: Dr. Jongryool Kim is currently serving as the research director of AI System Infra team at SK hynix Inc., located in San Jose, California. He has been conducting research and development of numerous advanced projects such as custom HBM, CXL Pooled memory, computational CXL memory, and object interface storage solution for AI/HPC systems. Additionally, he is a Science Advisory Board (SAB) member of Semiconductor Research Corporation (SRC) JUMP 2.0. Prior to this role, he had served as the cloud system architect at Samsung Mobile division developing and operating a Samsung Cloud data analytics system that manages and analyzes data from all Samsung devices such as smart phones, wearable devices, and home appliances around the world. Additionally, he worked with various R&D teams at Samsung SW R&D Center. He conducted research to improve network and storage IO performance in Cloud.

### 2:45-3:10pm: PIMnast: Balanced Data Placement for GEMV Acceleration with Processing-In-Memory
Speaker: Mohamed Ibrahim, Mahzabeen Islam, Shaizeen Aga (AMD)

### 3:10 – 3:30pm, Coffee Break

### 3:30-3:55pm: ACID Support for Compute eXpress Link Memory Transactions
Speaker: Ellis Giles (Coda Solutions, Adv. Arch. Lab), Peter Varman (Rice University)

### 3:55-4:20pm: Multi-level Memory-Centric Profiling on ARM Processors with ARM SPE
Speaker: Samuel Miksits, Ruimin Shi (KTH), Maya Gokhale (LLNL), Jacob Wahlgren, Gabin Schieffer, Ivy Peng (KTH)

### 4:20-4:45pm: Sum Reduction with OpenMP Offload on NVIDIA Grace-Hopper System
Speaker: Zheming Jin (ORNL)

### 4:45-5:10pm: GMTrans : Combining Scalable Address Translation with Locality Control 
Speaker: Yuqing Wang (University of Chicago), Swann Perarnau (Argonne National Laboratory), Andrew Chien (University of Chicago)

### 5:10-5:35pm: GMTrans : Symmetric Locality: Definition and Initial Results
Speaker: Giordan Escalona, Dylan McKellips, Chen Ding (University of Rochester)

----
### <a name="Intro"></a>Introduction
Recent developments of new memory technologies, such as high-bandwidth memory, non-volatile memory, and disaggregated memory, coupled with advanced high-performance interconnects like CXL and NVlink-c2c, further expand the memory hierarchy and increasingly blur the boundary between memory and storage. The growing disparity between computing speed and memory speed, commonly referred to as the Memory Wall problem, remains a critical and enduring challenge in the computing community. 

The prevalence of heterogeneous computing, ongoing advancements in the memory hierarchy, and the rise of disaggregated architectures significantly broaden the scope of the challenge of efficiently exploiting memory subsystems on large-scale parallel systems. Simultaneously, the proliferation of large machine learning models, graph processing, quantum computer simulations, and traditional scientific applications facing bottlenecks due to memory latency, bandwidth, and capacity constraints, continue to drive researchers, professionals, and practitioners to enhance memory system design and memory management. Computer architecture, operating systems, storage systems, middleware, performance models, tools, and applications are continuously being optimized or even redesigned to address the performance, programmability, and energy efficiency challenges of Memory Wall. Exploring the intersection of these research areas will enable cohesive and synergistic development and collaboration on the future of memory technologies, systems, middleware, and applications. 

This workshop aims to bring together computer science and computational science researchers, from industry, government labs, and academia, concerned with the challenges of efficiently using existing and emerging memory systems. The term performance for memory systems is general, which includes latency, bandwidth, power consumption, and reliability from the aspect of hardware memory technologies to how it is manifested in the application performance.

### <a name="topics"></a>Topics of Interest 
The topics of interest include, but are not limited to:

+ Evaluation, characterization, performance analysis, and use cases of emerging memory technologies, including non-volatile memories, high-bandwidth memory, heterogeneous memory, disaggregated memory, etc.

+ Software, hardware, and co-design approaches that ease the adoption and optimize the use of processing-in-memory and near-memory computing technologies.

+ Programming interfaces or language extensions that improve the programmability of using emerging memory technologies and systems, heterogeneous memory system and multi-dimensional data, and unified memory systems.

+ Compiler, runtime, and system techniques for optimizing data layout and placement, page migration, coherence and consistency enforcement, latency hiding and improving bandwidth utilization and energy consumption of heterogeneous memory systems.

+ Enhancement or new development for operating systems, storage and file systems, and I/O system that address challenges of existing and emerging memory technologies, heterogeneous memory systems, and the blurred boundary between memory and storage.

+ Tools, modeling, evaluation, and case study of memory system behavior and application performance that reveals the limitations and characteristics of existing memory systems.

+ Application development and optimization for new memory architecture and technologies and those overcome memory related challenges in their problems.

----
### <a name="dates"></a>Important Dates
 + Submission Deadline -- ~~July 25~~ August 09, 2024 (AoE)
 + Notifications -- ~~August 25~~ September 06, 2024 (FIRM)
 + Camera Ready Papers -- ~~September 15~~ September 27, 2024 (FIRM)
 + Workshop -- November 17, 2024
 
### <a name="org"></a>Organizers
 + Ron Brightwell (Sandia National Laboratories, USA)
 + Ivy Peng (KTH Royal Institute of Technology, Sweden)
 + Kyle Hale (Illinois Institute of Technology, USA)
 + Maya Gokhale (Lawrence Livermore National Laboratory, USA)
 
### <a name="pc"></a>Program Committee
 + Jeff Vetter (Oak Ridge National Laboratory, USA)
 + Jason Lowe-Power (University of California, Davis; Lawrence Berkeley National Laboratory, USA)
 + Thaleia Dimitra Doudali (IMDEA Software Institute, Spain)
 + Seyong Lee (Oak Ridge National Laboratory, USA)
 + Gwendolyn Voskuilen (Sandia National Laboratory, USA)
 + Jie Ren (College of William & Mary, USA)
 + Petar Radojkovic (Barcelona Supercomputing Center (BSC); Polytechnic University of Catalonia, Spain)
 + Shirley Moore (University of Texas, El Paso, USA)
 + Christian Pinto (IBM, Ireland) 

### <a name="submission"></a>Submission and Review Process
[Submission is Open](https://submissions.supercomputing.org). Login to SC'24 submission site, click 'Make a New Submission', choose MEMO'24. For SC24, IEEE is the SC proceeding publisher. Submissions must use the template of IEEE conference proceedings: two-column, US letter. The minimum number of pages is 5 pages, including references, and there is no upper limit of pages. IEEE will be providing a unique copyright submission site, and access to PDF eXpress to validate final pdfs. Additional guidelines, including the copyright notice for the camera-ready, will be provided at a later time. Camera ready papers are required to be formatted the same as the main conference papers. Each paper is expected to receive a minimum of 3 reviews. Double-blind peer-review will be used. Papers will be evaluated based on novelty, technical soundness, clarity of presentation, and impact. The Technical Program Committee reserves the right to reject incorrectly formatted papers.


