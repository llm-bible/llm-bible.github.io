---
layout: publication
title: 'Multi-range Reasoning For Machine Comprehension'
authors: Yi Tay, Luu Anh Tuan, Siu Cheung Hui
conference: "Arxiv"
year: 2018
bibkey: tay2018multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1803.09074"}
tags: ['Merging', 'Model Architecture', 'Reinforcement Learning']
---
We propose MRU (Multi-Range Reasoning Units), a new fast compositional
encoder for machine comprehension (MC). Our proposed MRU encoders are
characterized by multi-ranged gating, executing a series of parameterized
contract-and-expand layers for learning gating vectors that benefit from long
and short-term dependencies. The aims of our approach are as follows: (1)
learning representations that are concurrently aware of long and short-term
context, (2) modeling relationships between intra-document blocks and (3) fast
and efficient sequence encoding. We show that our proposed encoder demonstrates
promising results both as a standalone encoder and as well as a complementary
building block. We conduct extensive experiments on three challenging MC
datasets, namely RACE, SearchQA and NarrativeQA, achieving highly competitive
performance on all. On the RACE benchmark, our model outperforms DFN (Dynamic
Fusion Networks) by 1.5%-6% without using any recurrent or convolution layers.
Similarly, we achieve competitive performance relative to AMANDA on the
SearchQA benchmark and BiDAF on the NarrativeQA benchmark without using any
LSTM/GRU layers. Finally, incorporating MRU encoders with standard BiLSTM
architectures further improves performance, achieving state-of-the-art results.
