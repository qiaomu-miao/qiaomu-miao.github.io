---
title: Diffusion-Refined VQA Annotations for Semi-Supervised Gaze Following
date: '2024-10-01'
draft: false
publishDate: '2024-10-01'
authors:
- admin
- Alexandros Graikos
- Jingwei Zhang
- Sounak Mondal
- Minh Hoai
- Dimitris Samaras
url_pdf: https://arxiv.org/pdf/2406.02774
url_code: https://github.com/cvlab-stonybrook/GCDR-Gaze.git
publication_types:
- 'Conference'
abstract: <font size="2"> Training gaze following models requires a large number of images with gaze target coordinates annotated by human annotators, which is a laborious and inherently ambiguous process. We propose the first semi-supervised method for gaze following by introducing two novel priors to the task. We obtain the first prior using a large pretrained Visual Question Answering (VQA) model, where we compute Grad-CAM heatmaps by `prompting' the VQA model with a gaze following question. These heatmaps can be noisy and not suited for use in training. The need to refine these noisy annotations leads us to incorporate a second prior. We utilize a diffusion model trained on limited human annotations and modify the reverse sampling process to refine the Grad-CAM heatmaps. By tuning the diffusion process we achieve a trade-off between the human annotation prior and the VQA heatmap prior, which retains the useful VQA prior information while exhibiting similar properties to the training data distribution. Our method outperforms simple pseudo-annotation generation baselines on the GazeFollow image dataset. More importantly, our pseudo-annotation strategy, applied to a widely used supervised gaze following model (VAT), reduces the annotation need by 50%. </font>
featured: true
image:
  placement: 3
  caption: ''
  focal_point: "Left"
  preview_only: false
  filename: GCDR.png
publication: 'European Conference on Computer Vision (ECCV), 2024'
---