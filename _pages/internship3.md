## Using NVMe-over-Fabrics for efficient data storage in disaggregated datacenters

### Context

The architecture of datacenters evolves. To improve resource usage, disaggregated infrastructures are explored [1]. In these infrastructures, some servers host the computing resources while other servers are dedicated to storage. Solutions allowing to transfer data efficiently between the two types of nodes are required. This is challenging because for a disaggregated infrastructure to provide advantages, storage severs should only include processors with limited computing power.

NVMe SSD disks are more and more used in datacenters because of the performance advantage they provide. When used together with a high-performance network, they allow implementing NVMe-over-Fabrics (NVMe-oF) techniques, where a NVMe disk is accessed remotely as if it was part of the computing server.

Several solutions have been proposed to implement NVMe-oF [2,3]. Existing solutions offer different trade-offs between performance, resource consumption, and energy consumption. Furthermore, additional challenges related to the fault tolerance of the proposed solution appear, when implementing a disaggregated version of a storage service [4].


### Mission

In this internship, we would like to study the use of NVMe-oF to implement a reliable storage service for disaggregated datacenters, while studying the trade-off between 3 metrics: performance, resource usage, and energy consumption.

To this end, the intern will work on the following tasks:

- Analyzing existing NVMe-oF through a bibliographic review and through experiments on real hardware. The goal of this analysis will be twofold: i) Understanding the reliability guarantees offered by existing solutions; ii) evaluating their performance and resource consumption

- Based on the outputs of this first phase, the intern will then design a reliable storage solution for disaggregated datacenters, providing a standard key-value interface, with the goal of optimizing the trade-off between the 3 metrics

- If needed, the intern will have the opportunity to propose new optimizations to existing NVMe-oF to obtain a more efficient storage solution


For this work, the intern will get access to real hardware for running experiments through the Grid'5000 national testbed.





### References

[1] Marcos K. Aguilera, Emmanuel Amaro, Nadav Amit, Erika Hunhoff, Anil Yelam, and Gerd Zellweger. 2023. Memory disaggregation: why now and what are the challenges. SIGOPS Oper. Syst. Rev. 57, 1 (June 2023), 38–46.

[2] Yang, Ziye, et al. "SPDK: A development kit to build high performance storage applications." 2017 IEEE International Conference on Cloud Computing Technology and Science (CloudCom). IEEE, 2017.

[3] Endian Li, Shushu Yi, Li Peng, Qiao Li, Diyu Zhou, Zhenlin Wang, Xiaolin Wang et al. "SPDK+: Low Latency or High Power Efficiency? We Take Both." In Proceedings of the 17th ACM Workshop on Hot Topics in Storage and File Systems, pp. 17-23. 2025.

[4] Siying Dong, Shiva Shankar P, Satadru Pan, Anand Ananthabhotla, Dhanabal Ekambaram, Abhinav Sharma, Shobhit Dayal et al. "Disaggregating rocksdb: A production experience." Proceedings of the ACM on Management of Data 1, no. 2 (2023): 1-24.





### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
