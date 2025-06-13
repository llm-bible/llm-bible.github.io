---
layout: publication
title: 'Do Larger Language Models Imply Better Reasoning? A Pretraining Scaling Law For Reasoning'
authors: Xinyi Wang, Shawn Tan, Mingyu Jin, William Yang Wang, Rameswar Panda, Yikang Shen
conference: "Arxiv"
year: 2025
bibkey: wang2025do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.03635'}
tags: ['Reinforcement Learning', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
a wide range of tasks requiring complex reasoning. However, the effects of
scaling on their reasoning abilities remain insufficiently understood. In this
paper, we introduce a synthetic multihop reasoning environment designed to
closely replicate the structure and distribution of real-world large-scale
knowledge graphs. Our reasoning task involves completing missing edges in the
graph, which requires advanced multi-hop reasoning and mimics real-world
reasoning scenarios. To evaluate this, we pretrain language models (LMs) from
scratch solely on triples from the incomplete graph and assess their ability to
infer the missing edges. Interestingly, we observe that overparameterization
can impair reasoning performance due to excessive memorization. We investigate
different factors that affect this U-shaped loss curve, including graph
structure, model size, and training steps. To predict the optimal model size
for a specific knowledge graph, we find an empirical scaling that linearly maps
the knowledge graph search entropy to the optimal model size. This work
provides new insights into the relationship between scaling and reasoning in
LLMs, shedding light on possible ways to optimize their performance for
reasoning tasks.
