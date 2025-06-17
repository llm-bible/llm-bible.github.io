---
layout: publication
title: 'Mplug: Effective And Efficient Vision-language Learning By Cross-modal Skip-connections'
authors: Chenliang Li et al.
conference: EMNLP2022
year: 2022
citations: 92
bibkey: li2022effective
additional_links:
- name: Paper
  url: https://arxiv.org/abs/2205.12005
tags:
- Multimodal Models
- Transformer
- Efficiency and Optimization
- Pre-Training
---
Large-scale pretrained foundation models have been an emerging paradigm for
building artificial intelligence (AI) systems, which can be quickly adapted to
a wide range of downstream tasks. This paper presents mPLUG, a new
vision-language foundation model for both cross-modal understanding and
generation. Most existing pre-trained models suffer from the problems of low
computational efficiency and information asymmetry brought by the long visual
sequence in cross-modal alignment. To address these problems, mPLUG introduces
an effective and efficient vision-language architecture with novel cross-modal
skip-connections, which creates inter-layer shortcuts that skip a certain
number of layers for time-consuming full self-attention on the vision side.
mPLUG is pre-trained end-to-end on large-scale image-text pairs with both
discriminative and generative objectives. It achieves state-of-the-art results
on a wide range of vision-language downstream tasks, such as image captioning,
image-text retrieval, visual grounding and visual question answering. mPLUG
also demonstrates strong zero-shot transferability when directly transferred to
multiple video-language tasks.