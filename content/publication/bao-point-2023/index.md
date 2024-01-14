---
title: Point Cloud Plane Segmentation-Based Robust Image Matching for Camera Pose
  Estimation
authors:
- admin-JunqiBao
- admin
- Guoheng Huang
- Chan-Tong Lam
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
date: '2023-01-01'
publishDate: '2024-01-12T13:02:33.188374Z'
publication_types:
- article-journal
publication: "in *Remote Sensing* [JCR Q1]"
doi: 10.3390/rs15020497
abstract: The mainstream image matching method for recovering the motion of the camera
  is based on local feature matching, which faces the challenges of rotation, illumination,
  and the presence of dynamic objects. In addition, local feature matching relies
  on the distance between descriptors, which easily leads to lots of mismatches. In
  this paper, we propose a new robust image matching method for camera pose estimation,
  called IM_CPE. It is a novel descriptor matching method combined with 3-D point
  clouds for image matching. Specifically, we propose to extract feature points based
  on a pair of matched point cloud planes, which are generated and segmented based
  on depth images. Then, the feature points are matched based on the distance between
  their corresponding 3-D points on the point cloud planes and the distance between
  their descriptors. Moreover, the robustness of the matching can be guaranteed by
  the centroid distance of the matched point cloud planes. We evaluate the performance
  of IM_CPE using four well-known key point extraction algorithms, namely Scale-Invariant
  Feature Transform (SIFT), Speed Up Robust Feature (SURF), Features from Accelerated
  Segment Test (FAST), and Oriented FAST and Rotated Brief (ORB), with four sequences
  from the TUM RGBD dataset. According to the experimental results, compared to the
  original SIFT, SURF, FAST, and ORB algorithms, the NN_mAP performance of the four
  key point algorithms has been improved by 11.25%, 13.98%, 16.63%, and 10.53% on
  average, respectively, and the M.Score has also been improved by 25.15%, 23.05%,
  22.28%, and 11.05% on average, respectively. The results show that the IM_CPE can
  be combined with the existing key points extraction algorithms and the IM_CPE can
  significantly improve the performance of these key points algorithms.
tags:
- camera pose estimation
- image matching
- image segmentation
- key points extraction
- point cloud
links:
- name: URL
  url: https://www.mdpi.com/2072-4292/15/2/497
#projects:
#  - AI model Protection
---
