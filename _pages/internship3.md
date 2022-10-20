## Concurrent programming for CXL-based servers

### Tl;dr

* 3 month internship position at Univ. Grenoble Alpes (LIG laboratory)
* M1 internship
* Topic: multithread programming in CXL-based servers
* Goal: Design a lock algorithm that can work efficiently in systems based on CXL memory expanders

### Context

CXL is the new revolution in server architecture. It is new standard to interconnect all devices inside a server: the processors, the accelerators, the network cards, etc. Among other things, CXL is designed to overcome the memory limitations of current architectures. CXL will allow plugging memory expanders in servers to extend the memory capacity, and allow any device to access this memory in a cache-coherent manner. Having a cache-coherent globally shared memory between all computer devices open greats opportunities to design new efficient applications, but it also raises several new challenges from system point of view.

One of the challenges is concurrent programming. Traditionally, we have assumed that only the main processor was able to access the main memory, and that, this memory was directly attached to the main processor. But, what happens if multiple devices can access the main memory? And if the memory is not directly attached to the processor, but belongs to a dedicated memory expander device? The goal of this internship is to start studying this problem by considering the ubiquitous problem of mutual exclusion. 

### Mission

Please contact me for additional information

### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
