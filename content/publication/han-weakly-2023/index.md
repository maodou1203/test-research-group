---
title: Weakly supervised semantic segmentation of histological tissue via attention
  accumulation and pixel-level contrast learning
authors: 
- Yongqi Han
- Lianglun Cheng
- Guoheng Huang
- Guo Zhong
- Jiahua Li
- admin
- Hongrui Liu
- Jiao Li
- Jian Zhou
- Muyan Cai
author_notes:
- ""
- ""
- "corresponding author"
- "corresponding author"
- ""
- "corresponding author"
- "corresponding author"
- ""
- "corresponding author"
- "corresponding author"
date: '2023-02-01'
publishDate: '2024-01-12T13:02:33.198377Z'
publication_types:
- article-journal
publication: "in *Physics in Medicine & Biology* [SCI,JCR Q2]"
doi: 10.1088/1361-6560/acaeee
abstract: Objective. Histopathology image segmentation can assist medical professionals
  in identifying and diagnosing diseased tissue more efficiently. Although fully supervised
  segmentation models have excellent performance, the annotation cost is extremely
  expensive. Weakly supervised models are widely used in medical image segmentation
  due to their low annotation cost. Nevertheless, these weakly supervised models have
  difficulty in accurately locating the boundaries between different classes of regions
  in pathological images, resulting in a high rate of false alarms Our objective is
  to design a weakly supervised segmentation model to resolve the above problems.
  Approach. The segmentation model is divided into two main stages, the generation
  of pseudo labels based on class residual attention accumulation network (CRAANet)
  and the semantic segmentation based on pixel feature space construction network
  (PFSCNet). CRAANet provides attention scores for each class through the class residual
  attention module, while the Attention Accumulation (AA) module overlays the attention
  feature maps generated in each training epoch. PFSCNet employs a network model containing
  an inflated convolutional residual neural network and a multi-scale feature-aware
  module as the segmentation backbone, and proposes dense energy loss and pixel clustering
  modules are based on contrast learning to solve the pseudo-labeling-inaccuracy problem.
  Main results. We validate our method using the lung adenocarcinoma (LUAD-HistoSeg)
  dataset and the breast cancer (BCSS) dataset. The results of the experiments show
  that our proposed method outperforms other state-of-the-art methods on both datasets
  in several metrics. This suggests that it is capable of performing well in a wide
  variety of histopathological image segmentation tasks. Significance. We propose
  a weakly supervised semantic segmentation network that achieves approximate fully
  supervised segmentation performance even in the case of incomplete labels. The proposed
  AA and pixel-level contrast learning also make the edges more accurate and can well
  assist pathologists in their research.
links:
- name: URL
  url: https://dx.doi.org/10.1088/1361-6560/acaeee
---
