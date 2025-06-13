---
layout: publication
title: 'Progressive Collaborative And Semantic Knowledge Fusion For Generative Recommendation'
authors: Longtao Xiao, Haozhao Wang, Cheng Wang, Linfei Ji, Yifan Wang, Jieming Zhu, Zhenhua Dong, Rui Zhang, Ruixuan Li
conference: "Arxiv"
year: 2025
bibkey: xiao2025progressive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06269'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'GPT', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
With the recent surge in interest surrounding generative paradigms,
generative recommendation has increasingly attracted the attention of
researchers in the recommendation community. This paradigm generally consists
of two stages. In the first stage, pretrained semantic embeddings or
collaborative ID embeddings are quantized to create item codes, aiming to
capture and preserve rich semantic or collaborative knowledge within these
codes. The second stage involves utilizing these discrete codes to perform an
autoregressive sequence generation task. Existing methods often either overlook
collaborative or semantic knowledge, or combine the two roughly. In this paper,
we observe that naively concatenating representations from semantic and
collaborative modality leads to a semantic domination issue, where the
resulting representation is overly influenced by semantic information,
effectively overshadowing the collaborative representation. Consequently,
downstream recommendation tasks fail to fully exploit the knowledge from both
modalities, resulting in suboptimal performance. To address this, we propose a
progressive collaborative and semantic knowledge fusion model for generative
recommendation, named PRORec, which integrates semantic and collaborative
knowledge with a unified code through a two-stage framework. Specifically, in
the first stage, we propose a cross-modality knowledge alignment task, which
integrates semantic knowledge into collaborative embeddings, enhancing their
representational capability. In the second stage, we propose an in-modality
knowledge distillation task, designed to effectively capture and integrate
knowledge from both semantic and collaborative modalities. Extensive
experiments on three widely used benchmarks validate the effectiveness of our
approach, demonstrating its superiority compared to existing methods.
