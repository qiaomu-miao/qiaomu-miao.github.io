---
title: Patch-level gaze distribution prediction for gaze following
date: '2023-01-03'
draft: false
publishDate: '2023-01-03'
authors:
- admin
- Minh Hoai
- Dimitris Samaras
publication_types:
- 'Conference'
abstract: '<font size="2"> Gaze following aims to predict where a person is looking in a scene, by predicting the target location, or indicating that the target is located outside the image. Recent works detect the gaze target by training a heatmap regression task with a pixel-wise mean-square error (MSE) loss, while formulating the in/out prediction task as a binary classification task. This training formulation puts a strict, pixel-level constraint in higher resolution on the single annotation available in training, and does not consider annotation variance and the correlation between the two subtasks. To address these issues, we introduce the patch distribution prediction (PDP) method. We replace the in/out prediction branch in previous models with the PDP branch, by predicting a patch-level gaze distribution that also considers the outside cases. Experiments show that our model regularizes the MSE loss by predicting better heatmap distributions on images with larger annotation variances, meanwhile bridging the gap between the target prediction and in/out prediction subtasks, showing a significant improvement in performance on both subtasks on public gaze following datasets. </font>'
featured: false
url_pdf: https://openaccess.thecvf.com/content/WACV2023/papers/Miao_Patch-Level_Gaze_Distribution_Prediction_for_Gaze_Following_WACV_2023_paper.pdf
url_code: https://github.com/qiaomu-miao/gazefollowing_pdp
image:
  placement: 3
  caption: ''
  focal_point: ""
  preview_only: false
publication: '*Proceedings of the IEEE/CVF Winter Conference on Applications of Computer
  Vision (WACV)*'
---

