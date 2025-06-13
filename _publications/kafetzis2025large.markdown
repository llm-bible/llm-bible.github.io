---
layout: publication
title: 'Large Language Model Partitioning For Low-latency Inference At The Edge'
authors: Dimitrios Kafetzis, Ramin Khalili, Iordanis Koutsopoulos
conference: "Arxiv"
year: 2025
bibkey: kafetzis2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02533"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Large Language Models (LLMs) based on autoregressive, decoder-only
Transformers generate text one token at a time, where a token represents a
discrete unit of text. As each newly produced token is appended to the partial
output sequence, the length grows and so does the memory and compute load, due
to the expanding key-value caches, which store intermediate representations of
all previously generated tokens in the multi-head attention (MHA) layer. As
this iterative process steadily increases memory and compute demands,
layer-based partitioning in resource-constrained edge environments often
results in memory overload or high inference latency. To address this and
reduce inference latency, we propose a resource-aware Transformer architecture
partitioning algorithm, where the partitioning decision is updated at regular
intervals during token generation. The approach is myopic in that it is based
on instantaneous information about device resource availability and network
link bandwidths. When first executed, the algorithm places blocks on devices,
and in later executions, it migrates these blocks among devices so that the sum
of migration delay and inference delay remains low. Our approach partitions the
decoder at the attention head level, co-locating each attention head with its
key-value cache and allowing dynamic migrations whenever resources become
tight. By allocating different attention heads to different devices, we exploit
parallel execution of attention heads and thus achieve substantial reductions
in inference delays. Our experiments show that in small-scale settings (3-5
devices), the proposed method achieves within 15 to 20 percent of an exact
optimal solver's latency, while in larger-scale tests it achieves notable
improvements in inference speed and memory usage compared to state-of-the-art
layer-based partitioning approaches.
