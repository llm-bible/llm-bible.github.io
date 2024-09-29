---
layout: publication
title: Question-guided Hybrid Convolution For Visual Question Answering
authors: Gao Peng, Lu Pan, Li Hongsheng, Li Shuang, Li Yikang, Hoi Steven, Wang Xiaogang
conference: "Arxiv"
year: 2018
bibkey: gao2018question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1808.02632"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Reinforcement Learning']
---
In this paper we propose a novel Question-Guided Hybrid Convolution (QGHC) network for Visual Question Answering (VQA). Most state-of-the-art VQA methods fuse the high-level textual and visual features from the neural network and abandon the visual spatial information when learning multi-modal features.To address these problems question-guided kernels generated from the input question are designed to convolute with visual features for capturing the textual and visual relationship in the early stage. The question-guided convolution can tightly couple the textual and visual information but also introduce more parameters when learning kernels. We apply the group convolution which consists of question-independent kernels and question-dependent kernels to reduce the parameter size and alleviate over-fitting. The hybrid convolution can generate discriminative multi-modal features with fewer parameters. The proposed approach is also complementary to existing bilinear pooling fusion and attention based VQA methods. By integrating with them our method could further boost the performance. Extensive experiments on public VQA datasets validate the effectiveness of QGHC.
