---
title: Multi-view Gaze Target Estimation
date: '2025-08-07'
draft: false
publishDate: '2025-08-07'
weight: 1
authors:
- admin
- Vivek Raju Golani
- Jingyi Xu
- Progga Paromita Dutta
- Minh Hoai
- Dimitris Samaras
url_pdf: https://arxiv.org/pdf/2508.05857
links:
- name: "Webpage"
  url: "https://www3.cs.stonybrook.edu/~cvl/multiview_gte.html"
  icon: "globe"
  icon_pack: "fas"
publication_types:
- 'Conference'
abstract: <font size="2"> This paper presents a method that utilizes multiple camera views for the gaze target estimation (GTE) task. The approach integrates information from different camera views to improve accuracy and expand applicability, addressing limitations in existing single-view methods that face challenges such as face occlusion, target ambiguity, and out-of-view targets. Our method processes a pair of camera views as input, incorporating a Head Information Aggregation (HIA) module for leveraging head information from both views for more accurate gaze estimation, an Uncertainty-based Gaze Selection (UGS) for identifying the most reliable gaze output, and an Epipolar-based Scene Attention (ESA) module for cross-view background information sharing. This approach significantly outperforms single-view baselines, especially when the second camera provides a clear view of the person's face. Additionally, our method can estimate the gaze target in the first view using the image of the person in the second view only, a capability not possessed by single-view GTE methods. Furthermore, the paper introduces a multi-view dataset for developing and evaluating multi-view GTE methods. </font>
featured: true
image:
  placement: 3
  caption: ''
  focal_point: "Left"
  preview_only: false
  filename: GCDR.png
publication: '*International Conference on Computer Vision (ICCV)*, 2025'
---