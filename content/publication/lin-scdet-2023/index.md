---
title: 'SCDet: decoupling discriminative representation for dark object detection
  via supervised contrastive learning'
authors: 
- "Tongxu Lin"
- "Guoheng Huang"
- "admin"
- "Guo Zhong"
- "Xiaocong Huang"
- "Chi-Man Pun"
author_notes:
- ""
- "corresponding author"
- "corresponding author"
- ""
- ""
- ""
date: '2023-08-01'
publishDate: '2024-01-12T13:25:46.927107Z'
publication_types:
- article-journal
publication: "in *Visual Computer* [SCI,JCR Q2]"
doi: 10.1007/s00371-023-03039-x
abstract: 'Despite the significant progress made in object detection algorithms, their
  potential to operate effectively under the low-light environment remains to be fully
  explored. Recent methods realize dark object detection on the entire representation
  of dark images; however, they do not further consider the potential entanglement
  between dark disturbance and discriminative information in dark images, and thus,
  the learned representation may be sub-optimal. Towards this issue, we propose supervised
  contrastive detection (SCDet), a novel unified framework to learn the potential
  composition of dark images, and decouple the discriminative component for facilitating
  dark object detection. Specifically, we introduce the dense decoupling contrastive
  (DDC) pretext task to investigate the feature consistency based on a dark transformation,
  allowing the learned representation to be independent of the potential entanglement
  to realize decoupling. Moreover, to further drive the decoupled representation to
  be discriminative instead of a collapse solution for dark object detection, we incorporate
  the supervision detection task as an extra optimization objective, resulting in
  the joint optimization pattern. The two tasks are complementary to each other: the
  DDC task regularizes the detection to learn more decoupling-friendly representation,
  while the supervision detection task guides the discriminative representation decoupling.
  As a result, the SCDet achieves dark object detection by decoding the decoupled
  discriminative representation of dark images. Extensive experiments on four datasets
  demonstrate the effectiveness of our method in both synthetic and real-world scenarios.
  Code is available at https://github.com/TxLin7/SCDet.'
tags:
- Dark object detection
- Low-light environment
- Representation decoupling
- Supervised contrastive learning
links:
- name: URL
  url: https://doi.org/10.1007/s00371-023-03039-x
---
