## Reliable disaggregated cloud applications: RDMA + non-volatile memory

### Tl;dr

* 5-6 month internship position at Univ. Grenoble Alpes (LIG laboratory)
* M2 internship
* Topic: Disaggregated datacenters and non-volatile memory
* Goal: Design a solution to take advantage of non-volatile memory using RDMA in a disaggregated datacenter to build fault-tolerant applications.

### Context

Disaggregation is a promising approach to efficiently use resources in datacenters. The idea is to increase flexibility in resource management by allowing applications to use resources of other servers, in our case the memory, if they don't have enough resources on the servers they are running [1]. To implement such strategies, we need to rely on high performance networks that provide Remote Direct Memory Access (RDMA) to allow a processor to directly access the memory of a remote node [2]. 

On the other hand, emerging non-volatile memory technologies (NVMM), that provide unprecedented performance for a persistent device, are a great opportunity to implement highly efficient fault tolerance for cloud applications. In our team, we have designed ResPCT [3], which is, the most efficient existing fault-tolerant solution based on NVMM for cloud applications. ResPCT takes advantage of local NVMM modules to make applications fault tolerant. The goal of this internship is to extend ResPCT to be able to take advantage of remote NVMM through RDMA in the context of a disaggregated datacenter. 


### Mission

The intern will be in charge of the following tasks:

- Reviewing state-of-the-art techniques for accessing NVMM through RDMA, and organizing memory accesses in a disaggregated approach
- Designing a communication protocol to extend ResPCT checkpointing technique to the case where checkpoints are stored on a remote node
- Extending the approach to deal with the case where multiple nodes sharing the memory of the same remote node
- Evaluating the proposed solution on our experimental private cloud environment with real hardware, and with representative applications

The programming language used for this project will be C.

### References

[1] Tsai, Shin-Yeh, Yizhou Shan, and Yiying Zhang. "Disaggregating Persistent Memory and Controlling Them Remotely: An Exploration of Passive Disaggregated {Key-Value} Stores." 2020 USENIX Annual Technical Conference (USENIX ATC 20). 2020.

[2] Kalia, Anuj, David Andersen, and Michael Kaminsky. "Challenges and solutions for fast remote persistent memory access." Proceedings of the 11th ACM Symposium on Cloud Computing. 2020.

[3] Khorguani, Ana, Thomas Ropars, and Noel De Palma. "ResPCT: fast checkpointing in non-volatile memory for multi-threaded applications." Proceedings of the Seventeenth European Conference on Computer Systems. 2022.


### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
