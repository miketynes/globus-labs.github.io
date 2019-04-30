---
layout: project
title:  "Serverless Supercomputing"
image: "funcx.png"
teaser: "funcX is a Function as a Service platform for scientific computing."
featured: true
description: "funcX is a Function as a Service (FaaS) platform for science. It is designed to be applied to existing cyberinfrastructures to provide scalable, secure, and on-demand execution of short duration scientific functions."
---

Increasing data volumes and velocities are driving exciting new methods across the sciences in which data analytics and 
machine learning are increasingly intertwined with research. These new methods require new approaches for scientific 
computing in which computation is mobile, so that, for example, it can occur near data, be triggered by events (e.g., arrival of 
new data), or be offloaded to specialized accelerators. It also requires new design approaches in which monolithic applications 
can be decomposed into smaller components that may in turn be executed separately and on the most efficient resources. 
To address these needs we propose funcX---a high-performance Function as a Service (FaaS) platform that enables intuitive, flexible, 
efficient, scalable, and performant remote function execution on existing infrastructure including clouds, clusters, and supercomputers. 

funcX allows users to register and then execute Python functions without regard for the physical resource location, scheduler architecture, or virtualization technology on which the function is executed---an approach we refer to as "serverless supercomputing."
We have developed a prototype implementation of funcX and applied it to a range of scientific problems. We have also deployed it on two supercomputers, finding funcX to be capable of processing millions of functions and scaling to more than 65000 concurrent workers. 
