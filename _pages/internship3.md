## Improving the performance of disaggregated persistent memory using on-chip DMA

Reliability is a major concern in data centers. Non-volatile main memory (NVMM) is a new technology that can be used instead of DRAM but ensures the persistence of data even after a crash. Recently, several techniques have been proposed to use NVMM to build efficient fault tolerant systems [1]. These techniques assume that NVMM is available locally on the server where the application runs.

With the raise of disaggregation, this assumption might not hold anymore. In a disaggregated data center, some nodes host the computing resources while other nodes host the storage resources [2]. The storage nodes can include a lot of memory but little computing power.

In our team, we design solutions to use NVMM for fault tolerance in a disaggregated data center. This implies that we want to be able to copy the state of an application in a remote server, while using as little computing resource as possible on the remote server. To do so, we use the RDMA capabilities of modern network card to be able write into the memory of a remote server without the help of the remote CPU. However, to ensure data consistency even if a crash occurs in the middle of the saving operation, data need to be copied to remote NVMM in multiple steps. These multiple steps incur additional costs.

It has recently been demonstrated that on-chip DMA can be used to improve the performance of data transfers to NVMM [3]. On-chip DMAs can be used to transfer data to/from memory without intervention from the CPU. The goal of the internship is to study how such a solution could be used to improve the performance and reduce the CPU consumption of our solution to save data in remote NVMM.


### Mission

The intern will be in charge of the following tasks:

- Studying recent publications related to DMA and understand how DMA can be used for data transfer.

- Design a solution to use DMA to improve the performance of saving data in Remote Persistent Memory

- Implement the solution and evaluate its performance with real applications on our private cloud platform

### References

[1] A. Khorguani et al. *Respct: fast checkpointing in non-volatile memory for multi-threaded applications*. Proceedings of the Seventeenth European Conference on Computer Systems. 2022.

[2] M. Aguilera et al. *Memory disaggregation: why now and what are the challenges.* ACM SIGOPS Operating Systems Review (2023).

[3] J. Su et al. *Revitalizing the Forgotten On-Chip DMA to Expedite Data Movement in NVM-based Storage Systems*. 21st USENIX Conference on File and Storage Technologies (FAST 23). 2023.


### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
