---
layout: project
title:  "Distributed K-FAC"
image: "kfac.png"
teaser: "Deep Neural Network Training with Distributed K-FAC"
featured: false
description: "Kronecker-factored Approximate Curvature (K-FAC) can enable efficient second-order optimization and faster deep neural network training than traditional optimizers (e.g., SGD). Distributed K-FAC performs the expensive second-order computations in a model-parallel method to efficiently utilize HPC resources."
---

Training neural networks with many processors can reduce time-to-solution; however, it is challenging to maintain convergence and efficiency at large scales. The Kronecker-factored Approximate Curvature (K-FAC) was recently proposed as an approximation of the Fisher Information Matrix that can be used in natural gradient optimizers. We have developed a scalable K-FAC implementation and are exploring its applicability in convolutional neural network (CNN) training at scale. We are studying optimization techniques such as layer-wise distribution strategies, inverse-free second-order gradient evaluation, and dynamic K-FAC update decoupling to reduce training time while preserving convergence. We have applied our implementation to residual neural networks (ResNet) on the CIFAR-10 and ImageNet-1k datasets to evaluate the correctness and scalability of our K-FAC gradient preconditioner. With ResNet-50 on the ImageNet-1k dataset, our distributed K-FAC implementation converges to the 75.9% MLPerf baseline in 18-25% less time than does the classic stochastic gradient descent (SGD) optimizer across scales on a GPU cluster.

Try it out on [GitHub](https://github.com/gpauloski/kfac_pytorch).

Publications:
- J. Gregory Pauloski, Zhao Zhang, Lei Huang, Weijia Xu, and Ian T. Foster. 2020. [Convolutional neural network training with distributed K-FAC](https://arxiv.org/pdf/2007.00784.pdf). In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC ‘20). IEEE Press, Article 94, 1–14.
