---
layout: publication
title: 'A Template-guided Hybrid Pointer Network For Knowledge-basedtask-oriented Dialogue Systems'
authors: Dingmin Wang, Ziyao Chen, Wanwei He, Li Zhong, Yunzhe Tao, Min Yang
conference: "Arxiv"
year: 2021
bibkey: wang2021template
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.05830"}
tags: ['Applications']
---
Most existing neural network based task-oriented dialogue systems follow
encoder-decoder paradigm, where the decoder purely depends on the source texts
to generate a sequence of words, usually suffering from instability and poor
readability. Inspired by the traditional template-based generation approaches,
we propose a template-guided hybrid pointer network for the knowledge-based
task-oriented dialogue system, which retrieves several potentially relevant
answers from a pre-constructed domain-specific conversational repository as
guidance answers, and incorporates the guidance answers into both the encoding
and decoding processes. Specifically, we design a memory pointer network model
with a gating mechanism to fully exploit the semantic correlation between the
retrieved answers and the ground-truth response. We evaluate our model on four
widely used task-oriented datasets, including one simulated and three manually
created datasets. The experimental results demonstrate that the proposed model
achieves significantly better performance than the state-of-the-art methods
over different automatic evaluation metrics.
