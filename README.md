# Ultrascale
Python Based Agent-Based Simulation Framework supporting Large-Scale Computation and simple Integration with State-of-the-Art Machine Learning

**Ultrascale** is a general-purpose framework that enables agent-based simulation. Ultrascale is designed to tackle four main goals:
 
 1. Python-based scripting that is faimiliar to data science and machine learning practitioners. 
 Easy design of scenarios and behaviors, access to useful building blocks and utilities that enable fast prototyping and execution.
 Use of common API specifications, e.g. the use of Numpy or Pandas for data import etc, as well as import of (live-)data from web sources, e.g.
 OpenStreetMap etc.
 
 2. Enabling very large-scale (*ultrascale*) simulations. This is enabled by an efficient C++-based execution and communication backend.
 Secondly the support of modern large-scale  computation technolgies like Ray, Kubernetes etc. enables the distributed computation on
 machine clusters, while supporting the existing workflow and hardware of machine-learning focused developers. Support of cloud architectures.
 
 3. Out-of-the-box integration of modern machine-learning frameworks like PyTorch and Tensorflow to enable intelligent training of agents,
 with a particular focus on state-of-the-art *reinforcement learning* models.
 
 4. A easy-to-use API for data generation and export, e.g. for exploratory data analysis, pattern analysis and interactive visualizations.
 
 Ultrascale is **not** a complete software package, providing a GUI or targeted at specific use cases. While support for common use cases
 like e.g. spatial agent-absed modeling will be provided, the aim of the framework is to support generic agent-based scenarios.
