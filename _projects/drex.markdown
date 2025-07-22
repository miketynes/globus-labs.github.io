---

[comment]: # Do not change the layout
layout: project

[comment]: # Project title
title: "D-Rex"

[comment]: # The image should be added to images/projects/
image: "drex.png"

[comment]: # List of project members.
people: ["Maxime Gonthier", "Haochen Pan", "Hai Duc Nguyen", "Valerie Hayot-Sasson", "J. Gregory Pauloski", "Kyle Chard", "Ian Foster"]

[comment]: # List of project tags. Remove all that do not apply
hashtags: [
    "Fault Tolerance", "Reliability", "Distributed and Heterogeneous Data Storage", "Erasure Coding", "Load Balancing"
]

[comment]: # GitHub link or blank if not applicable
github: "https://github.com/dynostore/D-rex/tree/main"

[comment]: # Website/homepage/docs or blank if not applicable
website: ""

[comment]: # One-line teaser/description for front page/project page
teaser: "Algorithms and models for fast, reliable data storage using erasure coding with heterogeneous storage nodes"

[comment]: # Set to false if the project is no longer maintained
active: false

---

D-Rex proposes an innovative reliability model that uses the concept of a reliability target. This target is expressed as the probability of successfully accessing a data item within a given time interval. This model makes it easy for users to express and reason about quality-of-service guarantees.
The model contains two dynamic algorithms, D-Rex LB and D-Rex SC. These algorithms aim to solve the multi-objective optimization problem of storing as much data as possible while satisfying reliability and storage capacity targets and minimizing the I/O overhead associated with read/write operations.
Using diverse datasets, we ran extensive simulations and demonstrated that, on average, D-Rex SC and D-Rex LB store 45% and 31% more data, respectively, while operating at speeds that are only 0.4 and 0.3 MB/s slower than classic state-of-the-art algorithms when using heterogeneous nodes.

#### Publications
<!-- List the full citations for each paper here with links to where to find it. -->

- Maxime Gonthier, Dante D. Sanchez-Gallegos, Haochen Pan, Bogdan Nicolae, Sicheng Zhou, Hai Duc Nguyen, Valerie Hayot-Sasson, Greg Pauloski, Jesus Carretero, Kyle Chard, Ian Foster. 2025. [D-Rex: Heterogeneity-Aware Reliability Framework and Adaptive Algorithms for Distributed Storage](https://hpcrl.github.io/ICS2025-webpage/program/Proceedings_ICS25/ics25-52.pdf). In Proceedings of the ACM International Conference on Supercomputing (ICS 25). 

#### Funding and Acknowledgements
<!-- List any funding sources or other acknowledgements here otherwise remove -->
Based upon work supported by the U.S. Department of Energy (DOE), Office of Science, Office of Advanced Scientific Computing Research, under Contract DE-AC02-06CH11357. Partially funded by NSF, under Grant CSSI-2411386 and by MICIU/AEI-10.13039501100011033/ "FEDER Una manera de hacer Europa" under the project PID2022-138050NB-I00. We gratefully acknowledge the support of Chameleon Cloud for providing the computational resources (project CHI-231082).
