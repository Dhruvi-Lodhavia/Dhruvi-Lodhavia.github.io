---
title: "Internship - FPGA implementation of Accelerating the post-quantum algorithm - BIKE using Verilog"
excerpt: "Implemented the Black Gray Flip decoder belonging to the decapsulation process of BIKE - a post quantum crytography algorithm<br/><img src='/images/post-quantum-cryptography.jpg'>"
collection: projects
---

During my internship at Nanyang Technological University (NTU) with Prof. Anupam Chattopadhyay, I worked on FPGA implementation of Accelerating BIKE, a post-quantum cryptography algorithm using Verilog. BIKE is an alternate candidate, and is in consideration in the competition organized by the National Institute of Standards and Technology (NIST) for standardization of Post Quantum Cryptography (PQC). 

I understood the concepts of hardware security and the decapsulation process, reviewed its algorithm, and realized the need to accelerate it in order to implement it. The initial implementation was sequential, software-based, and unoptimized for hardware implementation. I understood the algorithm and its nuances and recognized specific hardware features I could leverage. I restructured RAM and the decoder architecture in order to parallelize operations. Using trade-off analysis between area and cycles for operation, I successfully reduced the number of LUTs and cycles required by 65% and 99.6%