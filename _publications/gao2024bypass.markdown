---
layout: publication
title: 'Bypass Back-propagation: Optimization-based Structural Pruning For Large Language Models Via Policy Gradient'
authors: Yuan Gao, Zujing Liu, Weizhong Zhang, Bo Du, Gui-song Xia
conference: "Arxiv"
year: 2024
bibkey: gao2024bypass
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.10576'}
tags: ['Reinforcement Learning', 'Pruning', 'Efficiency and Optimization', 'Training Techniques']
---
In contrast to moderate-size neural network pruning, structural weight
pruning on the Large-Language Models (LLMs) imposes a novel challenge on the
efficiency of the pruning algorithms, due to the heavy computation/memory
demands of the LLMs. Recent efficient LLM pruning methods typically operate at
the post-training phase without the expensive weight finetuning, however, their
pruning criteria often rely on heuristically hand-crafted metrics, potentially
leading to suboptimal performance. We instead propose a novel
optimization-based structural pruning that learns the pruning masks in a
probabilistic space directly by optimizing the loss of the pruned model. To
preserve the efficiency, our method eliminates the back-propagation through the
LLM per se during the optimization, requiring only the forward pass of the LLM.
We achieve this by learning an underlying Bernoulli distribution to sample
binary pruning masks, where we decouple the Bernoulli parameters from the LLM
loss, thus facilitating an efficient optimization via a policy gradient
estimator without back-propagation. As a result, our method is able to 1)
operate at structural granularities of channels, heads, and layers, 2) support
global and heterogeneous pruning (i.e., our method automatically determines
different redundancy for different layers), and 3) optionally initialize with a
metric-based method (for our Bernoulli distributions). Extensive experiments on
LLaMA, LLaMA-2, LLaMA-3, Vicuna, and Mistral using the C4 and WikiText2
datasets demonstrate that our method operates for 2.7 hours with around 35GB
memory for the 13B models on a single A100 GPU, and our pruned models
outperform the state-of-the-arts w.r.t. both perplexity and the majority of
various zero-shot tasks. Codes will be released.
