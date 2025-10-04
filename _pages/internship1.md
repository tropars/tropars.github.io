## On the carbon footprint of blob storage

In the context of global warming, reducing the carbon emissions of computer systems is a top priority. Data centers are responsible for a large fraction of the carbon emissions of IT. 

Storage is a significant contributor to the carbon footprint of data centers [1]. In a recent study, we have shown that the best type of storage (HDD vs SSD) when trying to minimize the carbon footprint is not necessarily SSDs [2]. The study was considering the case of key-value stores and showed that the answer is less obvious that it might look at first sight. Depending on the data access patterns, HDDs can be better than SSDs. The goal of this internship is to extend the study to the case of Blob storage.

Blob storage is one of the main types of storage used in Datacenter/Cloud environments [3]. it is used to store large binary files such as photos and videos. Hence, the data access pattern is very different from key-value stores.


### Mission

The intern will be in charge of the following tasks:

- Studying recent publications and collecting information about blob storage systems in Cloud environments

- Running experimental campaigns on our large-scale private Cloud platform, to analyze the energy/performance trade-off provided by different storage technologies for blob storage. Our platform is instrumented to be able to measure precisely the energy consumed by storage devices.

- Analyzing the results and propose strategies to reduce the carbon footprint of blob storage.


### References


[1] S. McAllister et al., *A call for research on storage emissions*. In Proceedings of the 3rd Workshop on Sustainable Computer Systems (HotCarbon), 2024.

[2] J. Nibler and T. Ropars, *Carbon Footprint of Storage in Data Centers: the Impact of Using Ssds for Key-Value Stores*. In 2025 IEEE 25th International Symposium on Cluster, Cloud and Internet Computing (CCGrid)

[3] S. Satija et al. *Cloudscape: A Study of Storage Services in Modern Cloud Architectures*. In 23rd USENIX Conference on File and Storage Technologies (FAST 25). 2025.


### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the KrakOS research team, that focus on the efficiency and robustness of systems. KrakOS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
