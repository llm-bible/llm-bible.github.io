---
layout: publication
title: 'Memory Augmented Language Models Through Mixture Of Word Experts'
authors: Cicero Nogueira Dos Santos, James Lee-thorp, Isaac Noble, Chung-ching Chang, David Uthus
conference: "Arxiv"
year: 2023
bibkey: santos2023memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10768"}
tags: ['Uncategorized']
---
Scaling up the number of parameters of language models has proven to be an
effective approach to improve performance. For dense models, increasing model
size proportionally increases the model's computation footprint. In this work,
we seek to aggressively decouple learning capacity and FLOPs through
Mixture-of-Experts (MoE) style models with large knowledge-rich vocabulary
based routing functions and experts. Our proposed approach, dubbed Mixture of
Word Experts (MoWE), can be seen as a memory augmented model, where a large set
of word-specific experts play the role of a sparse memory. We demonstrate that
MoWE performs significantly better than the T5 family of models with similar
number of FLOPs in a variety of NLP tasks. Additionally, MoWE outperforms
regular MoE models on knowledge intensive tasks and has similar performance to
more complex memory augmented approaches that often require to invoke custom
mechanisms to search the sparse memory.
