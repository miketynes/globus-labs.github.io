---
layout: project
title:  "Cost-aware computing"
image: "arch.png"
teaser: "Automating cost-aware profiling, prediction, and provisioning of cloud and HPC resources."
featured: false
description: "Cloud platforms are increasingly relied upon to conduct large scale science. However, the method by which infrastructure is provisioned and managed are ad hoc. We are developing new methods to profile application performance, predict cloud market conditions, and automate provisioning decisions."
---

Cloud computing has the potential to revolutionize scientific computing, much as it has transformed
enterprise information technology. By providing an elastically scalable pool of computing resources
that can be provisioned on demand or automatically, cloud computing can allow any researcher to perform even the largest
data analyses. Yet cloud computing is no panacea in its current form. First, it requires significant technical
knowledge to efficiently provision and manage cloud resources. Second, it can easily become expensive,
even when resource provisioning systems automatically provision and release resources as needed.

The Scalable Cost-Aware Cloud Infrastructure Management and Provisioning (SCRIMP) project aims to address
these challenges by developing new, more efficient cloud provisioning methods and integrating these
new methods into automated cloud and HPC access tools. In so doing, the project will improve the complexity, cost,
and efficiency of leveraging cloud computing platforms by an order of magnitude or more. 

Our research focuses on four core areas:
(1) developing new cloud profiling models that can efficiently predict application performance (execution
time, accuracy, and resource usage) across heterogeneous environments; 
(2) exploring cloud pricing and performance modeling to support provisioning of volatile instances at low cost 
and with low risk; and 
(3) creating an automated cost-aware provisioning service using serverless infrastructure to deploy tasks on diverse computing resources based on time, monetary, and service cost constraints. 

Further reading

- M. Baughman, R. Kumar, I. Foster, K. Chard, "Expanding Cost-Aware Function Execution with Multidimensional Notions of Cost". 1st Workshop on High Performance Serverless Computing. 2021.

- R. Kumar, M. Baughman, R. Chard, Z. Li, Y, Babuji, I. Foster, and K. Chard, "Coding the Computing Continuum: Fluid Function Execution in Heterogeneous Computing Environments". 30th Heterogeneity in Computing Workshop. 2021.

- M. Baughman, N. Chakubaji, H. Truong, K. Kreics, K. Chard, and I. Foster, ["Measuring, Quantifying, and Predicting the Cost-Accuracy Tradeoff"] (https://acris.aalto.fi/ws/portalfiles/portal/41076847/paper.pdf) 3rd IEEE International Workshop on Benchmarking, Performance Tuning, and Optimization for Big Data Applications. 2019.

- C. Wu, T. Summer, Z. Li, A. Woodard, R. Chard, M. Baughman, Y. Babuji, K. Chard, J. Pitt, and I. Foster, ["ParaOpt: Automated Application Parameterization and Optimization for the Cloud"] (https://labs.globus.org/pubs/wu-cloudcom-2019.pdf) IEEE International Conference on Cloud Computing Technology and Science. 2019.

- M. Baughman, S. Caton, C. Haas, R. Chard, R. Wolski, I. Foster, and K. Chard, ["Deconstructing the 2017 changes to AWS spot market pricing"] (https://labs.globus.org/pubs/Baughman_deconstructing_2019.pdf) 10th Workshop on Scientific Cloud Computing. 2019.

- M. Baughman, R. Chard, L. Ward, J. Pitt, K. Chard, and I. Foster, ["Profiling and Predicting Application Performance on the Cloud"] (https://labs.globus.org/pubs/Baughman_UCC_2018.pdf) 11th IEEE/ACM International Conference on Cloud Computing. 2018.

- M. Baughman, C. Haas, R. Wolski, I. Foster, and K. Chard, ["Predicting Amazon spot prices with LSTM networks"](https://labs.globus.org/pubs/Baughman_ScienceCloud_2018.pdf) 9th Workshop on Scientific Cloud Computing. 2018.

- R. Chard, K. Chard, R. Wolski, R. Madduri, B. Ng, K. Bubendorfer, and I. Foster, ["Cost-Aware Cloud Profiling, Prediction, and Provisioning as a Service,"](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7515692&isnumber=7515592) IEEE Cloud Computing 4 (4) : 48-59. 2017.
- R. Chard, K. Chard, B. Ng, K. Bubendorfer, A. Rodriguez, R. Madduri, and I. Foster, ["An Automated Tool Profiling Service for the Cloud,"](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7515692&isnumber=7515592) 2016 16th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing (CCGrid), Cartagena, 2016, pp. 223-232.
- R. Chard, K. Chard, K. Bubendorfer, L. Lacinski, R. Madduri and I. Foster, ["Cost-Aware Cloud Provisioning,"](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7304284&isnumber=7304061) e-Science (e-Science), 2015 IEEE 11th International Conference on, Munich, 2015, pp. 136-144.
- R. Wolski, J. Brevik, R. Chard, and K. Chard. [Probabilistic guarantees of execution duration for Amazon spot instances](https://www.researchgate.net/publication/320955546_Probabilistic_guarantees_of_execution_duration_for_Amazon_spot_instances). The International Conference for High Performance Computing, Networking, Storage and Analysis. 2017
