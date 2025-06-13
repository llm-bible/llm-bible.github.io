---
layout: publication
title: 'Heterrec: Heterogeneous Information Transformer For Scalable Sequential Recommendation'
authors: Hao Deng, Haibo Xing, Kanefumi Matsuyama, Yulei Huang, Jinxin Hu, Hong Wen, Jia Xu, Zulong Chen, Yu Zhang, Xiaoyi Zeng, Jing Zhang
conference: "Arxiv"
year: 2025
bibkey: deng2025heterogeneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01469"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods', 'Transformer']
---
Transformer-based sequential recommendation (TSR) models have shown superior
performance in recommendation systems, where the quality of item
representations plays a crucial role. Classical representation methods
integrate item features using concatenation or neural networks to generate
homogeneous representation sequences. While straightforward, these methods
overlook the heterogeneity of item features, limiting the transformer's ability
to capture fine-grained patterns and restricting scalability. Recent studies
have attempted to integrate user-side heterogeneous features into item
representation sequences, but item-side heterogeneous features, which are vital
for performance, remain excluded. To address these challenges, we propose a
Heterogeneous Information Transformer model for Sequential Recommendation
(HeterRec), which incorporates Heterogeneous Token Flatten Layer (HTFL) and
Hierarchical Causal Transformer Layer (HCT). Our HTFL is a novel item
tokenization method that converts items into a heterogeneous token set and
organizes these tokens into heterogeneous sequences, effectively enhancing
performance gains when scaling up the model. Moreover, HCT introduces
token-level and item-level causal transformers to extract fine-grained patterns
from the heterogeneous sequences. Additionally, we design a Listwise Multi-step
Prediction (LMP) Loss function to further improve performance. Extensive
experiments on both offline and online datasets show that the HeterRec model
achieves superior performance.
