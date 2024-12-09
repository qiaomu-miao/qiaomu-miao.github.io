---
title: Multi-person Multi-view Close Proximity Estimation

summary: Matched the same person across camera views using appearance features and multiview geometry. Estimated the close proximity of each person using the matched results and estimated human poses.
abstract: ""

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2020-12-20'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: ''

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  focal_point: Right
  placement: 3
  caption: 'Green box indicates close proximity with other people, while red box indicates no close proximity with anyone.'

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

<font size="3"> This project analyzes close proximity from videos captured from different views when multiple children were participating in group activities. We calculated the fundamental matrix from the keypoint matchings across views. Then we performed cross-view matching for the same person using the appearance features and geometry correlations between the keypoints, including epipolar and homography. A state-of-the-art person re-identification model was fine-tuned on this data to track the same person across the time frame. After extracting the keypoints and bounding boxes for all target persons, we built and trained a Siamese Multi Layer Perceptron (MLP) to regress the close proximity scores for each person in each minute. The model is able to regress reasonable close proximity estimations even given very unbalanced and noisy labels. </font>