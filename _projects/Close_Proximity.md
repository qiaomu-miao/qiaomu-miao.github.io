---
title: "Multi-person Multi-view Close Proximity Estimation"
excerpt: 'Close proximity estimation'
---
<br>
The project is aimed to analyze the close proximity of multiple children engaging in group activities based on the video captured from cameras in different views. We analyzed the video from scratch, starting from keypoint matching and calculating the fundamental matrix. 2D pose information was extracted using YOLO v4 and AlphaPose. The we performed cross-view matching using the appearance features of the person and geometry correlations between the keypoints of each person, including epipolar and homography. A state-of-the-art person re-identification model was fine-tuned on this data to track the same person across the time frame. After extracting the keypoints and bounding boxes of each person across time and frames, we built a Siamese Multi layer Perceptron (MLP) to regress the close proximity scores for each person in each minute. The model is able to regress reasonable close proximity estimations even given very unbalanced and noisy labels. 

