---
layout: publication
title: 'Flexllm: A System For Co-serving Large Language Model Inference And Parameter-efficient Finetuning'
authors: Gabriele Oliaro, Xupeng Miao, Xinhao Cheng, Vineeth Kada, Ruohan Gao, Yingyi Huang, Remi Delacourt, April Yang, Yingcheng Wang, Mengdi Wu, Colin Unger, Zhihao Jia
conference: "Arxiv"
year: 2024
bibkey: oliaro2024system
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.18789'}
  - {name: "Code", url: 'https://github.com/flexflow/FlexFlow/'}
tags: ['Large-Scale Training', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Pruning', 'Reinforcement Learning']
---
Finetuning large language models (LLMs) is essential for task adaptation, yet
serving stacks today isolate inference and finetuning on separate GPU clusters
-- wasting resources and under-utilizing hardware. We introduce FlexLLM, the
first system to co-serve LLM inference and PEFT-based finetuning on shared GPUs
by fusing computation at the token level. The static compilation optimizations
in FlexLLM -- dependent parallelization and graph pruning significantly shrink
activation memory, leading to end-to-end GPU memory savings by up to 80%. At
runtime, a novel token-level finetuning mechanism paired with a hybrid token
scheduler dynamically interleaves inference and training tokens within each
co-serving iteration, meeting strict latency SLOs while maximizing utilization.
In end-to-end benchmarks on LLaMA-3.1-8B, Qwen-2.5-14B, and Qwen-2.5-32B,
FlexLLM sustains the inference SLO requirements up to 20 req/s, and improves
finetuning throughput by 1.9-4.8x under heavy inference workloads and 2.5-6.8x
under light loads, preserving over 76% of peak finetuning progress even at peak
demand. The source code of FlexLLM is publicly available at
https://github.com/flexflow/FlexFlow/.
