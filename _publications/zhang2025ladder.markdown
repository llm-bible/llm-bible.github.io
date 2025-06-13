---
layout: publication
title: 'Ladder-residual: Parallelism-aware Architecture For Accelerating Large Model Inference With Communication Overlapping'
authors: Muru Zhang, Mayank Mishra, Zhongzhu Zhou, William Brandon, Jue Wang, Yoon Kim, Jonathan Ragan-kelley, Shuaiwen Leon Song, Ben Athiwaratkun, Tri Dao
conference: "Arxiv"
year: 2025
bibkey: zhang2025ladder
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.06589'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language model inference is both memory-intensive and time-consuming,
often requiring distributed algorithms to efficiently scale. Various model
parallelism strategies are used in multi-gpu training and inference to
partition computation across multiple devices, reducing memory load and
computation time. However, using model parallelism necessitates communication
of information between GPUs, which has been a major bottleneck and limits the
gains obtained by scaling up the number of devices. We introduce Ladder
Residual, a simple architectural modification applicable to all residual-based
models that enables straightforward overlapping that effectively hides the
latency of communication. Our insight is that in addition to systems
optimization, one can also redesign the model architecture to decouple
communication from computation. While Ladder Residual can allow
communication-computation decoupling in conventional parallelism patterns, we
focus on Tensor Parallelism in this paper, which is particularly bottlenecked
by its heavy communication. For a Transformer model with 70B parameters,
applying Ladder Residual to all its layers can achieve 29% end-to-end wall
clock speed up at inference time with TP sharding over 8 devices. We refer the
resulting Transformer model as the Ladder Transformer. We train a 1B and 3B
Ladder Transformer from scratch and observe comparable performance to a
standard dense transformer baseline. We also show that it is possible to
convert parts of the Llama-3.1 8B model to our Ladder Residual architecture
with minimal accuracy degradation by only retraining for 3B tokens. We release
our code for training and inference for easier replication of experiments.
