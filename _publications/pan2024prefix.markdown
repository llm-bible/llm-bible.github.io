---
layout: publication
title: 'Marconi: Prefix Caching For The Era Of Hybrid Llms'
authors: Rui Pan, Zhuang Wang, Zhen Jia, Can Karakus, Luca Zancato, Tri Dao, Yida Wang, Ravi Netravali
conference: "Arxiv"
year: 2024
bibkey: pan2024prefix
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19379'}
tags: ['Attention Mechanism', 'Language Modeling', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning']
---
Hybrid models that combine the language modeling capabilities of Attention
layers with the efficiency of Recurrent layers (e.g., State Space Models) have
gained traction in practically supporting long contexts in Large Language Model
serving. Yet, the unique properties of these models complicate the usage of
complementary efficiency optimizations such as prefix caching that skip
redundant computations across requests. Most notably, their use of in-place
state updates for recurrent layers precludes rolling back cache entries for
partial sequence overlaps, and instead mandates only exact-match cache hits;
the effect is a deluge of (large) cache entries per sequence, most of which
yield minimal reuse opportunities. We present Marconi, the first system that
supports efficient prefix caching with Hybrid LLMs. Key to Marconi are its
novel admission and eviction policies that more judiciously assess potential
cache entries based not only on recency, but also on (1) forecasts of their
reuse likelihood across a taxonomy of different hit scenarios, and (2) the
compute savings that hits deliver relative to memory footprints. Across diverse
workloads and Hybrid models, Marconi achieves up to 34.4\\(\times\\) higher token
hit rates (71.1% or 617 ms lower TTFT) compared to state-of-the-art prefix
caching systems.
