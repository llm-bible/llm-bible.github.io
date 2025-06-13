---
layout: publication
title: 'Emerging Pixel Grounding In Large Multimodal Models Without Grounding Supervision'
authors: Shengcao Cao, Liang-yan Gui, Yu-xiong Wang
conference: "Arxiv"
year: 2024
bibkey: cao2024emerging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08209"}
  - {name: "Code", url: "https://groundLMM.github.io"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Merging', 'Ethics and Bias', 'Has Code', 'Applications', 'Attention Mechanism']
---
Current large multimodal models (LMMs) face challenges in grounding, which
requires the model to relate language components to visual entities. Contrary
to the common practice that fine-tunes LMMs with additional grounding
supervision, we find that the grounding ability can in fact emerge in LMMs
trained without explicit grounding supervision. To reveal this emerging
grounding, we introduce an "attend-and-segment" method which leverages
attention maps from standard LMMs to perform pixel-level segmentation.
Furthermore, to enhance the grounding ability, we propose DIFFLMM, an LMM
utilizing a diffusion-based visual encoder, as opposed to the standard CLIP
visual encoder, and trained with the same weak supervision. Without being
constrained by the biases and limited scale of grounding-specific supervision
data, our approach is more generalizable and scalable. We achieve competitive
performance on both grounding-specific and general visual question answering
benchmarks, compared with grounding LMMs and generalist LMMs, respectively.
Notably, we achieve a 44.2 grounding mask recall on grounded conversation
generation without any grounding supervision, outperforming the extensively
supervised model GLaMM. Project page: https://groundLMM.github.io.
