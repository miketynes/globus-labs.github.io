---
layout: project
title:  "Colmena"
image: "colmena.svg"
teaser: "Machine Learning-Based Steering of Ensemble Simulations"
featured: false
description: "Colmena is a Python library for building applications that combine AI and simulation workflows on HPC. Its core feature is a communication library that simplifies tools for intelligently steering large ensemble simulations."
---

The core concept of Colmena is a “thinker” application.
The Thinker application is responsible for intelligently responding to new data, such as by updating a machine learning model or selecting a new simulation with Bayesian optimization.

Colmena provides a few main components to enable building thinker applications:

- A “Task Server” that provides a simplified interface to HPC-ready workflow systems.
- A high-performance queuing system for interacting with method server(s) from thinking applications.
- An extensible base class for building thinking applications with a dataflow programming model.

Try it out at:
[https://colmena.readthedocs.io](https://colmena.readthedocs.io)
