---
layout: publication
title: 'Bag Of Tricks For Inference-time Computation Of LLM Reasoning'
authors: Fan Liu, Wenshuo Chao, Naiqiang Tan, Hao Liu
conference: "Arxiv"
year: 2025
bibkey: liu2025bag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07191"}
  - {name: "Code", url: "https://github.com/usail-hkust/benchmark_inference_time_computation_LLM"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Prompting']
---
With the advancement of large language models (LLMs), solving complex
reasoning tasks has gained increasing attention. Inference-time computation
methods (e.g., Best-of-N, beam search, et al.) are particularly valuable as
they can enhance reasoning performance without modifying model parameters or
requiring additional training. However, these techniques come with
implementation challenges, and most existing methods remain at the
proof-of-concept stage with limited practical adoption due to their
computational complexity and varying effectiveness across different tasks. In
this paper, we investigate and benchmark diverse inference-time computation
strategies across reasoning tasks of varying complexity. Since most current
methods rely on a proposer-verifier pipeline that first generates candidate
solutions (e.g., reasoning solutions) and then selects the best one based on
reward signals (e.g., RLHF rewards, process rewards), our research focuses on
optimizing both candidate solution generation (e.g., instructing prompts,
hyperparameters such as temperature and top-p) and reward mechanisms (e.g.,
self-evaluation, reward types). Through extensive experiments (more than 20,000
A100-80G GPU hours with over 1,000 experiments) across a variety of models
(e.g., Llama, Qwen, and Mistral families) of various sizes, our ablation
studies reveal that previously overlooked strategies can significantly enhance
performance (e.g., tuning temperature can improve reasoning task performance by
up to 5%). Furthermore, we establish a standardized benchmark for
inference-time computation by systematically evaluating six representative
methods across eight reasoning tasks. These findings provide a stronger
foundation for future research. The code is available at
https://github.com/usail-hkust/benchmark_inference_time_computation_LLM
