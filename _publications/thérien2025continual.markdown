---
layout: publication
title: 'Continual Pre-training Of Moes: How Robust Is Your Router?'
authors: Benjamin Thérien, Charles-étienne Joseph, Zain Sarwar, Ashwinee Panda, Anirban Das, Shi-xiong Zhang, Stephen Rawls, Sambit Sahu, Eugene Belilovsky, Irina Rish
conference: "Arxiv"
year: 2025
bibkey: thérien2025continual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05029'}
tags: ['Transformer', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Model Architecture', 'Pre-Training', 'Pretraining Methods']
---
Sparsely-activated Mixture of Experts (MoE) transformers are promising
architectures for foundation models. Compared to dense transformers that
require the same amount of floating point operations (FLOPs) per forward pass,
MoEs benefit from improved sample efficiency at training time and achieve much
stronger performance. Many closed-source and open-source frontier language
models have thus adopted an MoE architecture. Naturally, practitioners will
want to extend the capabilities of these models with large amounts of newly
collected data without completely re-training them. Prior work has shown that a
simple combination of replay and learning rate re-warming and re-decaying can
enable the continual pre-training (CPT) of dense decoder-only transformers with
minimal performance degradation compared to full re-training. In the case of
decoder-only MoE transformers, however, it is unclear how the routing algorithm
will impact continual pre-training performance: 1) do the MoE transformer's
routers exacerbate forgetting relative to a dense model?; 2) do the routers
maintain a balanced load on previous distributions after CPT?; 3) are the same
strategies applied to dense models sufficient to continually pre-train MoE
LLMs? In what follows, we conduct a large-scale (>2B parameter switch and
DeepSeek MoE LLMs trained for 600B tokens) empirical study across four MoE
transformers to answer these questions. Our results establish a surprising
robustness to distribution shifts for both Sinkhorn-Balanced and
Z-and-Aux-loss-balanced routing algorithms, even in MoEs continually
pre-trained without replay. Moreover, we show that MoE LLMs maintain their
sample efficiency (relative to a FLOP-matched dense model) during CPT and that
they can match the performance of a fully re-trained MoE at a fraction of the
cost.
