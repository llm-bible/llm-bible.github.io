---
layout: publication
title: 'An Adaptive Placement And Parallelism Framework For Accelerating RLHF Training'
authors: Youshao Xiao, Zhenglei Zhou, Fagui Mao, Weichang Wu, Shangchun Zhao, Lin Ju, Lei Liang, Xiaolu Zhang, Jun Zhou
conference: "Arxiv"
year: 2023
bibkey: xiao2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11819"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT']
---
Recently, ChatGPT or InstructGPT like large language models (LLM) has made a
significant impact in the AI world. Many works have attempted to reproduce the
complex InstructGPT's training pipeline, namely Reinforcement Learning with
Human Feedback (RLHF). However, the mainstream distributed RLHF training
methods typically adopt a fixed model placement strategy, referred to as the
Co-located strategy. This strategy treats all four interdependent models
involved in RLHF as a single entity, distributing them across all devices and
applying parallelism techniques designed for a single model, regardless of the
workload heterogeneity inherent to each model. As a result, this strategy
exacerbates the generation bottlenecks in the RLHF training and degrades the
overall training efficiency. To address these issues, we propose a flexible
model placement framework that offers two general and agile model placement
strategies. The Interleaving strategy helps reduce memory redundancy and
communication costs of RLHF training by placing models without dependencies on
exclusive devices with careful orchestration. On the other hand, the
Disaggregated strategy improves the throughput of model training by separating
the training and inference runtime of the RLHF pipeline with additional shadow
models. Furthermore, our framework provides a simple user interface and
guidelines to easily and flexibly configure these strategies in various
training scenarios. Our experiments have shown that our strategy can achieve
notable improvements up to 11x, compared to the current state-of-the-art (SOTA)
approaches. The results highlight the effectiveness and adaptability of our
methods in accelerating the training of distributed RLHF.
