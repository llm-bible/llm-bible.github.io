---
layout: publication
title: 'SEEKR: Selective Attention-guided Knowledge Retention For Continual Learning Of Large Language Models'
authors: Jinghan He, Haiyun Guo, Kuan Zhu, Zihan Zhao, Ming Tang, Jinqiao Wang
conference: "Arxiv"
year: 2024
bibkey: he2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06171"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Distillation', 'Attention Mechanism']
---
Continual learning (CL) is crucial for language models to dynamically adapt
to the evolving real-world demands. To mitigate the catastrophic forgetting
problem in CL, data replay has been proven a simple and effective strategy, and
the subsequent data-replay-based distillation can further enhance the
performance. However, existing methods fail to fully exploit the knowledge
embedded in models from previous tasks, resulting in the need for a relatively
large number of replay samples to achieve good results. In this work, we first
explore and emphasize the importance of attention weights in knowledge
retention, and then propose a SElective attEntion-guided Knowledge Retention
method (SEEKR) for data-efficient replay-based continual learning of large
language models (LLMs). Specifically, SEEKR performs attention distillation on
the selected attention heads for finer-grained knowledge retention, where the
proposed forgettability-based and task-sensitivity-based measures are used to
identify the most valuable attention heads. Experimental results on two
continual learning benchmarks for LLMs demonstrate the superiority of SEEKR
over the existing methods on both performance and efficiency. Explicitly, SEEKR
achieves comparable or even better performance with only 1/10 of the replayed
data used by other methods, and reduces the proportion of replayed data to 1%.
