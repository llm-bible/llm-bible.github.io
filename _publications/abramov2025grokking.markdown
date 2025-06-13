---
layout: publication
title: 'Grokking In The Wild: Data Augmentation For Real-world Multi-hop Reasoning With Transformers'
authors: Roman Abramov, Felix Steinbauer, Gjergji Kasneci
conference: "Arxiv"
year: 2025
bibkey: abramov2025grokking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20752"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Applications']
---
Transformers have achieved great success in numerous NLP tasks but continue
to exhibit notable gaps in multi-step factual reasoning, especially when
real-world knowledge is sparse. Recent advances in grokking have demonstrated
that neural networks can transition from memorizing to perfectly generalizing
once they detect underlying logical patterns - yet these studies have primarily
used small, synthetic tasks. In this paper, for the first time, we extend
grokking to real-world factual data and address the challenge of dataset
sparsity by augmenting existing knowledge graphs with carefully designed
synthetic data to raise the ratio \\(\phi_r\\) of inferred facts to atomic facts
above the threshold required for grokking. Surprisingly, we find that even
factually incorrect synthetic data can strengthen emergent reasoning circuits
rather than degrade accuracy, as it forces the model to rely on relational
structure rather than memorization. When evaluated on multi-hop reasoning
benchmarks, our approach achieves up to 95-100% accuracy on 2WikiMultiHopQA -
substantially improving over strong baselines and matching or exceeding current
state-of-the-art results. We further provide an in-depth analysis of how
increasing \\(\phi_r\\) drives the formation of generalizing circuits inside
Transformers. Our findings suggest that grokking-based data augmentation can
unlock implicit multi-hop reasoning capabilities, opening the door to more
robust and interpretable factual reasoning in large-scale language models.
