---
layout: publication
title: 'Grass: Compute Efficient Low-memory LLM Training With Structured Sparse Gradients'
authors: Aashiq Muhamed, Oscar Li, David Woodruff, Mona Diab, Virginia Smith
conference: "Arxiv"
year: 2024
bibkey: muhamed2024compute
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17660"}
  - {name: "Code", url: "https://github.com/aashiqmuhamed/GRASS"}
tags: ['Efficiency and Optimization', 'RAG', 'Pruning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language model (LLM) training and finetuning are often bottlenecked by
limited GPU memory. While existing projection-based optimization methods
address this by projecting gradients into a lower-dimensional subspace to
reduce optimizer state memory, they typically rely on dense projection
matrices, which can introduce computational and memory overheads. In this work,
we propose Grass (GRAdient Stuctured Sparsification), a novel approach that
leverages sparse projections to transform gradients into structured sparse
updates. This design not only significantly reduces memory usage for optimizer
states but also minimizes gradient memory footprint, computation, and
communication costs, leading to substantial throughput improvements. Extensive
experiments on pretraining and finetuning tasks demonstrate that Grass achieves
competitive performance to full-rank training and existing projection-based
methods. Notably, Grass enables half-precision pretraining of a 13B parameter
LLaMA model on a single 40GB A100 GPU--a feat infeasible for previous
methods--and yields up to a \\(2\times\\) throughput improvement on an 8-GPU
system. Code can be found at https://github.com/aashiqmuhamed/GRASS .
