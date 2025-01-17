# CXL-related

## 1. CXL Paper

1. Meta TPP: Transparent Page Placement protocol and Chameleon memory tracking 

2. MS zNUMA: First-generation Memory Disaggregation for Cloud Platforms

3. KAIST DirectCXL: Direct Access, High-Performance Memory Disaggregation with DirectCXL

4. CXL-SSD: Hello bytes, bye blocks- PCIe storage meets compute express link for memory expansion

6. Pond: CXL-Based Memory Pooling Systems for Cloud Platforms


## 2. Industry Vendor Memory Models

1. Compute Express Link Overview

2. ARM: Synchronization Overview and Case Study on Arm Architecture



## 3. Related Works (e.g. RDMA)

1. Cache Coherence: Rethinking Software Runtimes for Disaggregated Memory.

2. Spark on Disaggreagated Memory: Optimizing Performance and Computing Resource Management of in-memory Big Data Analytics with Disaggregated Persistent Memory

3. Persistence Semantics for Weak Memory


## 4. Related Books

1. A Primer on Memory Consistency and Cache Coherence

2. Shared Memory Synchronization

3. Quorum Systems With Applications to Storage and Consensus

4. Database Replication


## 5. Open Source Tools

1. Open Source SSD/NVM etc. simulators.  http://camelab.org/pmwiki.php?n=Main.Tools

2. Arch Concurrency Test. http://diy.inria.fr/doc/litmus.html

3. A working example of how to use the herd7 Memory Model Tool. https://community.arm.com/arm-community-blogs/b/architectures-and-processorsblog/posts/how-to-use-the-memory-model-tool

4. How to generate litmus tests automatically with the diy7 tool. https://community.arm.com/arm-community-blogs/b/architectures-and-processorsblog/posts/generate-litmus-tests-automatically-diy7-tool  http://diy.inria.fr/doc/gen.html

5. Running litmus tests on hardware using litmus7. https://community.arm.com/arm-community-blogs/b/architectures-and-processorsblog/posts/running-litmus-tests-on-hardware-litmus7 https://github.com/Compute-Express-Link/litmustestgen

6. Murphi for Modeling. http://mclab.di.uniroma1.it/site/index.php/software/18-cmurphi

7. Alloy, Express axiomatic specifications of consistency models. http://alloy.mit.edu

8. Express axiomatic specifications of consistency models Cat, associated with the Herd tool. http://diy.inria.fr/herd/ . 

9. The spec domain specific language allows for pipeline and coherence protocol implementations to be specified axiomatically http://check.cs.princeton.edu/#tools . 

10. The ppcmem tool (https://www.cl.cam.ac.uk/~pes20/ppcmem/help.html) does something similar but is specialized for POWER and ARM memory models

11. CppMem tool (http://svr- pes20-cppmem.cl.cam.ac.uk/cppmem/) is geared toward the C/C++ language-level memory model. 
 
12. As far as operational models are concerned, the RMEM tool (https://www.cl.cam. ac.uk/~sf502/regressions/rmem/) has built-in operational models for ARM (multiple vari- ants), POWER (multiple variants), x86-TSO and RISC-V, and also allows for their behaviors to be explored.

13. MemSynth (http: //memsynth.uwplse.org/) shows how a complete memory model satisfying the litmus tests can be synthesized.
