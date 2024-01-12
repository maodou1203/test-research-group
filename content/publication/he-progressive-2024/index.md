---
title: Progressive normalizing flow with learnable spectrum transform for style transfer
authors: 
- Zixuan He
- Guoheng Huang
- admin
- Guo Zhong
- Chi-Man Pun
- Yiwen Zeng
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- ""
date: '2024-01-01'
publishDate: '2024-01-12T13:25:46.869356Z'
publication_types:
- article-journal
publication: 'in *Knowledge-Based Systems* [SCI,JCR Q1]'
doi: 10.1016/j.knosys.2023.111277
abstract: Most current style transfer models are designed as encoder–decoder structures.
  Some encoding operations, such as downsampling and pooling, cause a loss of image
  details. If the encoder and decoder are not compatible, it can also introduce distortion.
  Reversible neural networks have demonstrated their superior power in lossless projection.
  However, since the inputs and outputs of neural flows are holistic features, merely
  the high-level features can be utilized for image generation through reverse inference.
  These high-level features emphasize the image style more, leading to the generated
  results easily losing content details and producing abstract colors. To address
  the above issues, we propose LSTFlow, the first progressive reversible neural network
  capable of feature decomposition. First, LSTFlow incorporates our proposed reversible
  Learnable Spectrum Transform (LST), which can dynamically decompose the feature
  into feature spectrum and recover them losslessly. LSTFlow can retain more details
  by enabling multi-level features to be fused in backward inference. Second, we propose
  a Progressive Flow Stylization Strategy (PFSS) to balance the model’s emphasis between
  content and style and enhance the color perception. Forward inference based PFSS
  is carried out progressively, while the backward inference focuses on progressive
  generation. To demonstrate the effectiveness of our proposed method, we conducted
  comparative experiments with seven other state-of-the-art algorithms. The stylized
  effects are evaluated in terms of visual effects and quantitative indicators. The
  experiments show that the lightest LSTFlow performs the best in SSIM, Color Entropy,
  Color Uniformity and FID indicators and outperforms state-of-the-art methods.
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S0950705123010250
---
