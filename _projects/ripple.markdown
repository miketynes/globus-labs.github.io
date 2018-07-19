---
layout: project
title:  "Ripple"
image: "ripple-new.png"
teaser: "We are developing methods to automate the provisioning of cloud computing infrastructure"
featured: true
description: "Ripple is an automation framework designed to managing data throughout its lifecycle, in which users specify via high-level rules and the actions to be performed on data at different times and locations."
---

Researchers are faced with an increasingly complex data landscape in which data are obtained from a number of different sources (e.g., instruments, computers, published data), stored in disjoint storage systems, and analyzed on an area of high performance and cloud computers. Given the increasing speed at which data are produced, combined with increasingly complex scientific processes and the requisite data management, munging, and organization activities required to make sense of data, researchers are faced with new bottlenecks in the discovery process. Improving data lifecycle management practices is essential to enhancing productivity, facilitating reproducible research, and encouraging collaboration. We posit that researchers require automated methods for managing their data such that tedious and repetitive tasks (e.g., transferring, archiving, and analyzing) are accomplished without continuous user input.

Ripple aims to allow researchers, lab managers, and administrators to define data management practices as a set of simple if-trigger-then-action recipes. Actions, such as moving data or executing an analysis script, are triggered in response to events, such as files being created, modified, or deleted. Filesystem events are captured through various APIs, including Linux’s inotify and the Globus API. Given the broad range of actions that might be possible
Ripple builds upon severless computing systems to enable on-demand processing of recipes. In particular, using Amazon Web Services Lambda as a scalable and low-latency solution for performing arbitrary, loosely coupled actions.

Our research focuses on three core areas:
(1) Developing novel, and reliable, event monitoring solutions for extremely large leadership storage devices;
(2) investigating serverless computing's ability to provide a service which reliably coordinates the execution of tasks over thousands of distributed endpoints; and 
(3) exploring techniques and programming models which enable non-technical users to design and configure custom flows of data.

Try it out at:
[https://ripple.globuscs.info](https://ripple.globuscs.info)

Further reading

- R. Chard, K. Chard, S. Tuecke, and I. Foster, [Software Defined Cyberinfrastructure for Data Management](https://www.researchgate.net/publication/321120695_Software_Defined_Cyberinfrastructure_for_Data_Management). 13th International Conference on e-Science, 2017.
- A. K. Paul, R. Chard, K. Chard, S. Tuecke, A. R. Butt, and I. Foster, [Toward Scalable Monitoring on Large-Scale Storage for
Software Defined Cyberinfrastructure](https://www.researchgate.net/publication/320808893_Toward_Scalable_Monitoring_on_Large-Scale_Storage_for_Software_Defined_Cyberinfrastructure). Proceedings of the 2nd Joint International Workshop on Parallel Data Storage & Data Intensive Scalable Computing Systems, 2017.
- I. Foster, B. Blaiszik, K. Chard, and R. Chard [Software Defined Cyberinfrastructure](https://www.researchgate.net/publication/317695594_Software_Defined_Cyberinfrastructure). The 37th IEEE International Conference on Distributed Computing Systems, 2017.
- R. Chard, K. Chard, J. Alt, D. Y. Parkinson, S. Tuecke, and I. Foster, [RIPPLE: Home Automation for Research Data Management](https://www.researchgate.net/publication/317333251_RIPPLE_Home_Automation_for_Research_Data_Management). First International Workshop on Serverless Computing (WoSC), 2017.
