---
title: "How to Train Neural Field Representations: A Comprehensive Study and Benchmark"
collection: publications
permalink: /publication/2024-02-01-paper-title-number-5
venue: 'Accepted at CVPR'
paperurl: 'https://arxiv.org/pdf/2312.10531'
image_path: '/images/fit-a-nef.png'
---

*Neural fields (NeFs) have recently emerged as a versatile method for modeling signals of various modalities, including images, shapes, and scenes. Subsequently, a number of works have explored the use of NeFs as representations for downstream tasks, e.g. classifying an image based on the parameters of a NeF that has been fit to it. However, the impact of the NeF hyperparameters on their quality as downstream representation is scarcely understood and remains largely unexplored. This is in part caused by the large amount of time required to fit datasets of neural fields.
In this work, we propose a JAX-based library that leverages parallelization to enable fast optimization of large-scale NeF datasets, resulting in a significant speed-up. With this library, we perform a comprehensive study that investigates the effects of different hyperparameters on fitting NeFs for downstream tasks. In particular, we explore the use of a shared initialization, the effects of overtraining, and the expressiveness of the network architectures used. Our study provides valuable insights on how to train NeFs and offers guidance for optimizing their effectiveness in downstream applications. Finally, based on the proposed library and our analysis, we propose Neural Field Arena, a benchmark consisting of neural field variants of popular vision datasets, including MNIST, CIFAR, variants of ImageNet, and ShapeNetv2. Our library and the Neural Field Arena will be open-sourced to introduce standardized benchmarking and promote further research on neural fields.*

[PDF from arxiv](https://arxiv.org/pdf/2312.10531)

Samuele Papa, Riccardo Valperga, David Knigge, Miltiadis Kofinas, Phillip Lippe, Jan-Jakob Sonke, Efstratios Gavves

