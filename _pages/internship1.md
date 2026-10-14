## On the carbon footprint of fault-tolerant storage in the cloud

In the context of global warming, reducing the carbon emissions of computer systems is a top priority. Data centers are responsible for a large fraction of the carbon emissions of IT. 

Storage is a significant contributor to the carbon footprint of data centers [1]. To ensure the availability of data despite hardware failures, cloud providers employ replication techniques, sometimes at multiple levels (intra-datacenter and cross-datacenter replication [2]). But replication amplifies resource usage and therefore increases carbon footprint. Some techniques, such as erasure coding techniques [3] and advanced RAID techniques [4], can help reducing the storage footprint of replication at the cost of a performance decrease. However, slowing-down applications can also be prejudicial to the overall carbon footprint of the system.

The goal of this internship is to study and compare replications techniques for reliable data storage in datacenters, to understand and optimize the trade-off between performance and carbon footprint.


### Mission

The intern will be in charge of the following tasks:

- Studying recent publications and collecting information about replication techniques in Cloud storage systems

- Running experimental campaigns on our large-scale private Cloud platform, to analyze the energy/storage footprint/performance trade-off provided by different reliable storage techniques. Our platform is instrumented to be able to measure precisely the energy consumed by storage devices.

- Analyzing the results and propose strategies to reduce the carbon footprint of cloud storage.


### References


[1] S. McAllister et al., *A call for research on storage emissions*. In Proceedings of the 3rd Workshop on Sustainable Computer Systems (HotCarbon), 2024.

[2] S. Noghabi et al., “Ambry: Linkedin’s scalable geo-distributed object store,” in Proceedings of the 2016 ACM SIGMOD International Conference on Management of Data (SIGMOD), 2016, pp. 253–265.

[3] S. Muralidhar et al., “F4: Facebook’s warm blob storage system,” in Proceedings of the 11th USENIX Symposium on Operating Systems Design and Implementation (OSDI), 2014, pp. 383–398.

[4] Zhiyue Li, et al. "Flash-oriented coded storage: Research status and future directions". ACM Transactions on Storage, 2025




### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the KrakOS research team, that focus on the efficiency and robustness of systems. KrakOS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
