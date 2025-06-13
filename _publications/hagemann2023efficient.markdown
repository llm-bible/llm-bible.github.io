---
layout: publication
title: 'Efficient Parallelization Layouts For Large-scale Distributed Model Training'
authors: Johannes Hagemann, Samuel Weinbach, Konstantin Dobler, Maximilian Schall, Gerard De Melo
conference: "Arxiv"
year: 2023
bibkey: hagemann2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05610"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Large-Scale Training', 'Training Techniques', 'Attention Mechanism']
---
Efficiently training large language models requires parallelizing across
hundreds of hardware accelerators and invoking various compute and memory
optimizations. When combined, many of these strategies have complex
interactions regarding the final training efficiency. Prior work tackling this
problem did not have access to the latest set of optimizations, such as
FlashAttention or sequence parallelism. In this work, we conduct a
comprehensive ablation study of possible training configurations for large
language models. We distill this large study into several key recommendations
for the most efficient training. For instance, we find that using a micro-batch
size of 1 usually enables the most efficient training layouts. Larger
micro-batch sizes necessitate activation checkpointing or higher degrees of
model parallelism and also lead to larger pipeline bubbles. Our most efficient
configurations enable us to achieve state-of-the-art training efficiency
results over a range of model sizes, most notably a Model FLOPs utilization of
70.5% when training a Llama 13B model.
