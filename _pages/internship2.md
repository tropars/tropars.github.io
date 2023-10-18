## A lightweight and general Machine-Learning model to predict micro-service resource consumption

### Tl;dr

* 2 to 6 months internship position at Univ. Grenoble Alpes (LIG laboratory)
* M1 or M2 internship
* Topic: Performance of micro-service applications
* Goal: Building a machine-learning model that can accurately predict the resource consumption of microservices, while requiring small amount of data to train and being able to generalize to new hardware.

### Context

As the micro-service application model becomes popular in the Cloud domain, more and more large-scale micro-services applications are deployed in datacenters [1]. For such complex applications, a challenge at execution time is to find a good hardware and software configuration, that can ensure expected performance without consuming to many resources. Another challenge is to adapt this configuration dynamically based on the current load experienced by the application [2, 3].

In our team, we study how Machine Learning can help tackling this problem. Our approach is as follows: use our expertise about micro-services applications to build models that can work better than brute-force approaches that would not take the characteristics of such applications into account. At the core of our approach is a model that, for a given micro-service, is able to predict the resource consumption of the service for a given load.

We have already developed such a micro-service model. It gives promising results. The goal of the internship is to study and design techniques to improve the capabilities of this model. Multiple challenges still need to be tackled. Here is a non exhaustive list of the problems that still need to be tackled: 
- Since micro-services can be upgraded frequently in a continuous delivery approach, we need a model that can be trained and re-trained fast to adapt to these changes
- To achieve accurate predictions on different platform, we need a model that is able to generalize to new hardware
- To obtain a model that can be useful for a large set of applications, we need a model that can generalize to new applications



### Mission

The goal of the internship is to work on improving our micro-service model. The intern will be in charge of the following tasks:

- Reviewing the related work on the topic to determine what are the most promising approaches to improve of our model
- Proposing and applying methods to improve the capabilities of our model on one or several of the aspects listed above
- Running experiments at scale on a private cloud platform to collect the data required to train and evaluate the proposed model
- Conducting a detailed evaluation of the proposed model


### References

[1] Gan, Yu, et al. "An open-source benchmark suite for microservices and their hardware-software implications for cloud & edge systems." Proceedings of the Twenty-Fourth International Conference on Architectural Support for Programming Languages and Operating Systems. 2019.

[2] Chow, Ka-Ho, et al. "DeepRest: deep resource estimation for interactive microservices." Proceedings of the Seventeenth European Conference on Computer Systems. 2022.

[3] Luo, Shutian, et al. "The power of prediction: Microservice auto scaling via workload learning." Proceedings of the 13th Symposium on Cloud Computing. 2022.


### Location

The intern will join the Informatics Laboratory of Univ. Grenoble
Alpes (LIG), one of the largest laboratory in Computer Science in
France. Univ. Grenoble Alpes is one of the 50 best universities in the
world for computer science according to international rankings.

More specifically, the intern will work in the ERODS research team, that focus on the efficiency and robustness of distributed systems. ERODS is one of the top system research teams in France and in Europe, with publications in the most selective conferences of the domain.

### Contact

 - Thomas Ropars (<thomas.ropars@univ-grenoble-alpes.fr>)
