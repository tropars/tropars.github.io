## Energy efficiency and reliability in datacenters: is faster always better?

### Tl;dr

* 2-6 month internship position at Univ. Grenoble Alpes (LIG laboratory)
* M1 or M2 internship
* Topic: Energy efficiency of fault tolerance techniques in datacenters
* Goal: Analyze and compare the efficiency of different fault tolerance techniques in datacenters from energy point of view.

### Context

In the context of global warming, reducing the carbon emissions of computer infrastructures is a top priority. Datacenters are responsible for a large fraction of the carbon emissions of IT. 

To reduce the carbon footprint of datacenters, actions at multiple levels need to be taken. The way of managing and using the hardware should change [1]. However, efforts made only at the hardware level will not be enough to solve the challenges we are facing: software design needs to be made carbon aware [2]. A good example that illustrates the challenges we are facing is reliability and storage. To ensure the availability of data in the Cloud despite crashes, data are replicated on different storage devices. To make data storage more efficient, SSDs can be used instead of HDDs. However, when considering the total carbon footprint, including the carbon emissions required to build the devices, it is not clear anymore than using SSDs is better [3]. To answer this question, many parameters need to be taken into account: The carbon footprint related to the construction of the devices; the energy consumption of the software running on these devices; the quantity of work per energy unit that a software solution running on a given hardware can achieve; the impact of each solution on the other software components in the system, etc.

Considering the reliable storage of data in datacenters, the goal of this internship is to analyze the carbon footprint of different approaches and, if possible, to propose a new approach that would reduce the carbon emissions.

### Mission

The intern will be in charge of the following tasks:

- Studying recent publications and collecting information about the carbon footprint of current hardware.
- Running experimental campaigns on our large-scale private Cloud platform, to analyze the energy/performance trade-ff provided by different hardware and software solutions for the reliable storage of data.
- Analyzing the results to propose a strategy to reduce the carbon footprint of reliable storage approaches

For this internship, a scripting language (shell or python) will be used to automatize the experiments.


### References


[1] Tomlinson, Amanda, and George Porter. "Something Old, Something New: Extending the Life of CPUs in Datacenters."

[2] Anderson, Thomas, et al. "Treehouse: A Case For Carbon-Aware Datacenter Software." arXiv preprint arXiv:2201.02120 (2022).

[3] Tannu, Swamit, and Prashant J. Nair. "The Dirty Secret of SSDs: Embodied Carbon." arXiv preprint arXiv:2207.10793 (2022).


### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
