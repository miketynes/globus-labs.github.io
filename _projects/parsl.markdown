---
layout: project
title:  "Parsl"
image: "parsl-logo.png"
teaser: "Parallel scripting in Python"
featured: false
description: "Parsl is a parallel scripting library for Python. It provides a model by which complex workflows can be represented in an intuitive Python-based control application. It facilitates transparent parallel execution of workflow components (apps) on any distributed or parallel computing system."
---

Parsl is a Python-based parallel scripting library that supports development and execution of asynchronous and parallel data-oriented workflows (dataflows). These workflows glue together existing executables (called Apps) and Python functions with control logic written in Python. Parsl brings implicit parallel execution to standard Python scripts. Rather than explicitly defining a graph and/or modifying data structures, instead developers simply annotate Python functions and Apps. Parsl constructs a dynamic, parallel execution graph derived from the implicit linkage between Apps based on shared input/output data objects. Parsl then executes these components when dependencies are met. Parsl is resource-independent, that is, the same Parsl script can be executed on your laptop through to clusters, clouds, and supercomputers. Parsl also supports different executors including local threads, pilot jobs, and extreme-scale execution with Swift/T.

Parsl can be used to realize a variety of workflows:

- Parallel task-based workflows in which tasks are executed when their dependencies are met.
- Interactive and dynamic workflows in which the workflow is dynamically expanded during execution by users or the workflow itself.
- Procedural workflows in which serial execution of tasks are managed by Parsl.
- Workflows with many short duration tasks where no task-level fault tolerance is required
- Workflows with long running tasks with fault tolerance

Try it out at:
[https://parsl-project.org](https://parsl-project.org)

Further reading

- Babuji, Y., Brizius, A., Chard, K., Foster, I., Katz, D.S., Wilde, M., & Wozniak, J.. (2017, August 30). 
[Introducing Parsl: A Python Parallel Scripting Library](http://doi.org/10.5281/zenodo.853491). Zenodo. http://doi.org/10.5281/zenodo.853491.

Funding

- NSF 1550588
