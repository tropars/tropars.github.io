## Performance of concurrent algorithms: a carbon footprint perspective

### Tl;dr

* 2 to 6 months internship position at Univ. Grenoble Alpes (LIG laboratory)
* M1 or M2 internship
* Topic: Performance of concurrent algorithms
* Goal: Analyzing the carbon footprint of concurrent algorithms

### Context

In the context of global warming, reducing the carbon emissions of computer infrastructures is a top priority. Some improvements will come from the hardware, but improvements at the software level are also required [1]. 

Concurrent algorithms are at the core of computer software today as their purpose is to allow applications to take advantage of multi-core processors. For ubiquitous concurrent data structures such as queues, lists, or hash tables, a large number of implementations exists. These implementations have been extensively studied considering classical performance metrics such as throughput [2]. We would like to look at concurrent algorithms from another perspective: their carbon footprint.

To be able to analyze the carbon footprint of concurrent algorithms, we first need to identify the data that we need to collect to be able to estimate the carbon footprint. Multiple components in the system might need to be monitored including the processor and the memory [3]. Then, a methodology needs to be developed to collect the data. Modern hardware implement performance counters that allow obtaining precise information about the activity of the system. We have already developed tools to collect such counters, but they might need to be extended for the need of this study. Finally experiments and analysis will have to be conducted to understand what characteristics of concurrent algorithms make them more carbon-footprint efficient. 

### Mission

The intern will be in charge of the following tasks:

- Study recent publications to understand how the carbon footprint of concurrent algorithms should be measured

- Define and implement a methodology to evaluate the carbon footprint of concurrent algorithms

- Conduct experiments and compare results obtained on different hardware

To run experiments, the intern will get access to a large set of servers with different processor architectures

### References

[1] Anderson, Thomas, et al. "Treehouse: A Case For Carbon-Aware Datacenter Software." arXiv preprint arXiv:2201.02120 (2022).

[2] Gramoli, Vincent. "More than you ever wanted to know about synchronization: Synchrobench, measuring the impact of the synchronization on concurrent algorithms." Proceedings of the 20th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming. 2015.

[3] Köhler, Sven, et al. "Carbon-Aware Memory Placement." Proceedings of the 2nd Workshop on Sustainable Computer Systems. 2023.


### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
