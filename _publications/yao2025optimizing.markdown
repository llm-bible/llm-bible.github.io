---
layout: publication
title: 'Optimizing Chain-of-thought Reasoners Via Gradient Variance Minimization In Rejection Sampling And RL'
authors: Jiarui Yao, Yifan Hao, Hanning Zhang, Hanze Dong, Wei Xiong, Nan Jiang, Tong Zhang
conference: "Arxiv"
year: 2025
bibkey: yao2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02391"}
  - {name: "Code", url: "https://github.com/RLHFlow/GVM"}
tags: ['Fine-Tuning', 'Agentic', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Chain-of-thought (CoT) reasoning in large language models (LLMs) can be
formalized as a latent variable problem, where the model needs to generate
intermediate reasoning steps. While prior approaches such as iterative
reward-ranked fine-tuning (RAFT) have relied on such formulations, they
typically apply uniform inference budgets across prompts, which fails to
account for variability in difficulty and convergence behavior. This work
identifies the main bottleneck in CoT training as inefficient stochastic
gradient estimation due to static sampling strategies. We propose GVM-RAFT, a
prompt-specific Dynamic Sample Allocation Strategy designed to minimize
stochastic gradient variance under a computational budget constraint. The
method dynamically allocates computational resources by monitoring prompt
acceptance rates and stochastic gradient norms, ensuring that the resulting
gradient variance is minimized. Our theoretical analysis shows that the
proposed dynamic sampling strategy leads to accelerated convergence guarantees
under suitable conditions. Experiments on mathematical reasoning show that
GVM-RAFT achieves a 2-4x speedup and considerable accuracy improvements over
vanilla RAFT. The proposed dynamic sampling strategy is general and can be
incorporated into other reinforcement learning algorithms, such as GRPO,
leading to similar improvements in convergence and test accuracy. Our code is
available at https://github.com/RLHFlow/GVM.
