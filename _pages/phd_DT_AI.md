## Towards self-healing large scale distributed systems based on digital twins

### Summary

* 3-year PhD position at Univ. Grenoble Alpes (LIG laboratory)
* Keywords: Distributed systems, High availability, AI, Digital Twins
* Goal: Studying the digital twins approach as a mean to improving the
  self-healing capabilities of large-scale distributed systems.
* PhD done in collaborations with industrial partners


### Context

Distributed IT infrastructures keep increasing in scale and complexity. Very large scale systems (Data centers, Edge platforms, Supercomputers) are challenging to operate because they raise performance issues, failure management issues, and resource management issues. Being able to efficiently deal with failure in these systems is at the same time crucial and very complex. It is crucial because the frequency of failures increases with the scale of the infrastructures [1], and these failures can impair the availability of the system. It is very complex because identifying the root cause of the failures is a major problem [2], and predicting these failures, to limit their impact on the users, is even more difficult [3].

To build a highly-available large-scale infrastructure despite potentially frequent hardware and software failures, self-configuring, self-healing, and self-optimizing properties are required. In fact, these infrastructures are so complex that it is extremely difficult for human operators to fix problems *manually*. Hence, solutions based on autonomic computing [4], that allow a system to constantly adapt itself to changing conditions, are a promising approach in this context. However, because distributed IT infrastructures are hierarchical systems where a large number of software and hardware components interact, it can be difficult to decide what is the best action to take to handle a failure event (Which service should be reconfigured to improve the performance of my system [5]?) or to take consistent decisions when they are taken in a distributed manner.

Artificial Intelligence (AI) is a promising approach to help solving problems related to the availability and the self-healing of distributed infrastructures. Among the numerous research directions related to the use of AI in this context, we are more specifically interested in designing solutions based on AI to: i) detect and even predict failures in large scale distributed systems; ii) ensure the high availability of these systems despite failures through the implementation of consistent self-healing strategies. Recent works using AI to improve the performance and/or the reliability of distributed systems show that such approaches are very promising [6,7]. 

### Mission

Two main research directions are identified for this PhD thesis. Only one of the two research directions or the two of them will be investigated during the PhD, depending on the interests of the candidate and on the research opportunities.

The first research direction is about the detection and the prediction of failures in large scale distributed systems using AI. In this context, the goal will be to explore the concept of Digital Twin and its application to the management of distributed systems. A Digital Twin [8, 9] is a digital representation of a physical system that runs in parallel with the real system, and whose state is updated based on sensors values coming from the real system. Hence, the main purpose of a Digital Twin is to provide an accurate representation of the real system state to facilitate its analysis. The challenge would be to design solutions to build Digital Twins of large-scale distributed systems, and to exploit these Digital Twins to identify and predict failures in the real systems. This could involve building a hierarchy of Digital Twins to take into account the hierarchical nature of modern distributed systems. AI would be used to build accurate models [10] of some of the building blocks (servers, storage, network interconnect, etc.) of the distributed infrastructures.


The second research direction is about the design of solutions based on AI for the autonomic management of distributed infrastructures, with a focus on self-healing properties. The goal will be to build solutions based on AI that are able to learn the best actions to take to automatically correct problems created by failures in the system, and hence, to improve the availability and the efficiency of large scale infrastructures. The accurate representation of the system state, thanks to the Digital Twin approach, should allow to better identify the root cause of failures and to take better reconfiguration decisions. The convergence between AI and autonomic computing is a new research domain that could have a significant impact in the management of large scale infrastructures.


### Working conditions

The candidate will integrate the ERODS research team, which includes researchers, engineers, and PhD students with a high degree of expertise in the performance and the reliability of distributed systems. Through regular meetings, he/she will have the opportunity to present his/her work and to discuss research ideas with the other members of the team.

To conduct his/her research, the candidate will get access to large scale distributed infrastructures, including Cloud infrastructures. The candidate will also get the chance to discuss regularly with our industrial partner to obtain new insights about problems faced in production systems, and to get feedback on the practical applicability of the proposed solutions.

The candidate will also (optionally) get the opportunity to work as teaching assistant in the CS faculty at UGA. He/She could also be involved in the supervision of Master students.


### Location

The PhD student will join the Informatics Laboratory of
Univ. Grenoble Alpes, one of the largest laboratory in Computer
Science in France. 

### Job information

- **Position**: PhD.
- **Duration**: 3 years (starting date: before the end of 2021).
- **Location**: Grenoble, France.
- **Laboratory**: Informatics Laboratory of Univ. Grenoble Alpes.
   (<https://www.liglab.fr/>), Erods research team.

### Requirements

- M2 (or equivalent) in Computer Science
- Background in distributed systems and/or artificial intelligence
- Background in operating systems and/or computer architecture is a plus
- Ability to work independently
- Good communication skills
- Good command in spoken and written English

### Contact

- Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
- Noel De Palma (<noel.depalma@univ-grenoble-alpes.fr>) 



### References

- [1] Guosai Wang, Lifei Zhang, and Wei Xu. 2017. What can we learn from four years of data center hardware failures?. In 47th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN). IEEE, 25–36.
- [2] David Jauk, Dai Yang, and Martin Schulz. 2019. Predicting faults in high performance computing systems: an in-depth survey of the state-of-the-practice. In SuperCcomputing.
- [3] Anwesha Das, Frank Mueller, Paul Hargrove, Eric Roman, and Scott Baden. 2018. Doomsday: Predicting which node will fail when on supercomputers. In SuperComputing.
- [4] Jeffrey O. Kephart and David M. Chess. The Vision of Autonomic Computing. IEEE Computer, 36:41–50, January 2003.
- [5] Gan Y, Zhang Y, Hu K, Cheng D, He Y, Pancholi M, Delimitrou C. Seer: Leveraging big data to navigate the complexity of performance debugging in cloud microservices. In ASPLOS 2019.
- [6] Liang, Chieh-Jan Mike, et al. "AutoSys: The Design and Operation of Learning-Augmented Systems." 2020 USENIX Annual Technical Conference.
- [7] Alipourfard, Omid, et al. "Cherrypick: Adaptively unearthing the best cloud configurations for big data analytics." 14th USENIX Symposium on Networked Systems Design and Implementation. 2017.
- [8] Hochhalter, Jacob, William P. Leser, John A. Newman, Vipul K. Gupta, Vesselin Yamakov, Stephen R. Cornell, Scott A. Willard, and Gerd Heber. "Coupling Damage-Sensing Particles to the Digitial Twin Concept." (2014).
- [9] Uhlenkamp, Jan-Frederik, et al. "Digital Twin Applications: A first systemization of their dimensions." 2019 IEEE International Conference on Engineering, Technology and Innovation (ICE/ITMC). IEEE, 2019.
- [10] Niggemann, Oliver, et al. "The DigitalTwin from an Artificial Intelligence Perspective." arXiv preprint arXiv:2010.14376 (2020).
