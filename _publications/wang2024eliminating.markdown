---
layout: publication
title: 'Domino: Eliminating Communication In LLM Training Via Generic Tensor Slicing And Overlapping'
authors: Guanhua Wang, Chengming Zhang, Zheyu Shen, Ang Li, Olatunji Ruwase
conference: "Arxiv"
year: 2024
bibkey: wang2024eliminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15241"}
tags: ['Training Techniques', 'Reinforcement Learning']
---
Given the popularity of generative AI, Large Language Models (LLMs) often
consume hundreds or thousands of GPUs for parallelizing and accelerating the
training process. Communication overhead becomes more pronounced when training
LLMs at scale. To eliminate communication overhead in distributed LLM training,
we propose Domino, which provides a generic scheme to hide communication behind
computation. By breaking data dependency of a single batch training into
smaller independent pieces, Domino pipelines these independent pieces training
and provides generic strategy of fine-grained communication and computation
overlapping. Extensive results show that, comparing with Megatron-LM, Domino
achieves up to 1.3x speedup for LLM training on Nvidia DGX-H100 GPUs.
