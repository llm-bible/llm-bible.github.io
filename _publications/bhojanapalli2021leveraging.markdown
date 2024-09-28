---
layout: publication
title: Leveraging redundancy in attention with Reuse Transformers
authors: Bhojanapalli Srinadh, Chakrabarti Ayan, Veit Andreas, Lukasik Michal, Jain Himanshu, Liu Frederick, Chang Yin-wen, Kumar Sanjiv
conference: "Arxiv"
year: 2021
bibkey: bhojanapalli2021leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.06821"}
tags: ['ARXIV', 'Applications', 'Transformer']
---
Pairwise dot product-based attention allows Transformers to exchange information between tokens in an input-dependent way and is key to their success across diverse applications in language and vision. However a typical Transformer model computes such pairwise attention scores repeatedly for the same sequence in multiple heads in multiple layers. We systematically analyze the empirical similarity of these scores across heads and layers and find them to be considerably redundant especially adjacent layers showing high similarity. Motivated by these findings we propose a novel architecture that reuses attention scores computed in one layer in multiple subsequent layers. Experiments on a number of standard benchmarks show that reusing attention delivers performance equivalent to or better than standard transformers while reducing both compute and memory usage.
