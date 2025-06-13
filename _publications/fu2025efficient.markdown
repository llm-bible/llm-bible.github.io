---
layout: publication
title: 'Efficient And Adaptive Simultaneous Speech Translation With Fully Unidirectional Architecture'
authors: Biao Fu, Donglei Yu, Minpeng Liao, Chengxi Li, Yidong Chen, Kai Fan, Xiaodong Shi
conference: "Arxiv"
year: 2025
bibkey: fu2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11809"}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture']
---
Simultaneous speech translation (SimulST) produces translations incrementally
while processing partial speech input. Although large language models (LLMs)
have showcased strong capabilities in offline translation tasks, applying them
to SimulST poses notable challenges. Existing LLM-based SimulST approaches
either incur significant computational overhead due to repeated encoding of
bidirectional speech encoder, or they depend on a fixed read/write policy,
limiting the efficiency and performance. In this work, we introduce Efficient
and Adaptive Simultaneous Speech Translation (EASiST) with fully unidirectional
architecture, including both speech encoder and LLM. EASiST includes a
multi-latency data curation strategy to generate semantically aligned SimulST
training samples and redefines SimulST as an interleaved generation task with
explicit read/write tokens. To facilitate adaptive inference, we incorporate a
lightweight policy head that dynamically predicts read/write actions.
Additionally, we employ a multi-stage training strategy to align speech-text
modalities and optimize both translation and policy behavior. Experiments on
the MuST-C En\\(\rightarrow\\)De and En\\(\rightarrow\\)Es datasets demonstrate that
EASiST offers superior latency-quality trade-offs compared to several strong
baselines.
