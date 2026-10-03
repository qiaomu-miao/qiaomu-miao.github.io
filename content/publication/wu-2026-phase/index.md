---
title: Phase-Aligned RoPE for Mixed-Resolution Diffusion Transformer
date: '2026-09-08'
draft: false
publishDate: '2026-09-08'
weight: 2
authors:
- Haoyu Wu
- Jingyi Xu
- admin
- Dimitris Samaras
- Hieu Le
url_pdf: https://arxiv.org/pdf/2511.19778
links:
- name: "Webpage"
  url: "https://hao-yu-wu.github.io/mixed_res/"
  icon: "globe"
  icon_pack: "fas"
publication_types:
- 'Conference'
abstract: '<font size="2"> Rotary positional embeddings (RoPE) are widely used in diffusion transformers (DiTs) to encode spatial relationships, yet their behavior with mixed-resolution tokens remains underexplored. A natural approach is to rescale token positions from different resolutions into a unified coordinate system before attention, but we show this fails. Our analysis shows that with RoPE, the attention similarity score is a highly structured and periodic function of token distance, so rescaling distances across resolutions moves token pairs to different regions of this periodic function, leading to incorrect attention scores. Motivated by this, we introduce Phase-Aligned Mixed-Resolution Attention (PMA), a training-free mechanism that stabilizes mixed-resolution attention. PMA modifies the RoPE position mapping to enforce a consistent positional scale for every query-key pair, ensuring that relative distances are evaluated under a single reference scale. To further improve local coherence near resolution transitions, we incorporate a lightweight boundary refinement module that softly exchanges features across adjacent scales. Experiments on image and video diffusion models validate our analysis and demonstrate consistent improvements in visual fidelity and computational efficiency. </font>'
featured: false
publication: '*European Conference on Computer Vision (ECCV)*, 2026'
---
