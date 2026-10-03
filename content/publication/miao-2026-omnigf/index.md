---
title: 'OmniGF: A Dual-Branch Vision-Language Framework for Unified Gaze Following'
date: '2026-05-26'
draft: false
publishDate: '2026-05-26'
weight: 1
authors:
- admin
- Haoyu Wu
- Jingyi Xu
- Minh Hoai
- Dimitris Samaras
url_pdf: https://arxiv.org/pdf/2605.26399
url_code: https://github.com/cvlab-stonybrook/omnigf
publication_types:
- 'Conference'
abstract: '<font size="2"> Understanding human gaze behavior is essential for complex scene comprehension and human-computer interaction. Traditional gaze following models are typically restricted to pure spatial localization, lacking the high-level capacity to reason about semantic targets or complex social contexts. Furthermore, these models often process individuals sequentially, requiring redundant computations over the same scene image for multi-person inference. While recent Vision-Language Models (VLMs) offer the exceptional semantic reasoning needed to address gaze-related semantic tasks, their reliance on discrete text generation inherently limits precision in continuous spatial tasks like gaze localization. To bridge this gap, we propose OmniGF, a unified vision-language framework that adapts foundational VLMs for highly scalable multi-person gaze reasoning. The model adopts a dual-branch decoding strategy: a structured language branch generates discrete reasoning states, while a continuous spatial branch directly taps into the VLM''s dense hidden states. Supervising these extracted representations with high-resolution gaze target heatmaps effectively overcomes the spatial bottleneck of text-only coordinate generation. Furthermore, to explicitly ground the model in multi-person scenes, we augment the input with head embeddings encoded from cropped head images, providing fine-grained appearance and orientation cues for all individuals simultaneously. By modeling all individuals and leveraging the strong semantic capability of VLMs, OmniGF seamlessly integrates precise spatial gaze target estimation, semantic gaze prediction, and complex social gaze reasoning. Extensive experiments demonstrate that our framework establishes new state-of-the-art performance across multiple standard benchmarks. </font>'
featured: true
publication: '*Conference on Neural Information Processing Systems (NeurIPS)*, 2026 (Spotlight)'
---
