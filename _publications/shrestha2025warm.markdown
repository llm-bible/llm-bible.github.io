---
layout: publication
title: 'Warm Up Before You Train: Unlocking General Reasoning In Resource-constrained Settings'
authors: Safal Shrestha, Minwu Kim, Aadim Nepal, Anubhav Shrestha, Keith Ross
conference: "Arxiv"
year: 2025
bibkey: shrestha2025warm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13718"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Distillation']
---
Designing effective reasoning-capable LLMs typically requires training using Reinforcement Learning with Verifiable Rewards (RLVR) or distillation with carefully curated Long Chain of Thoughts (CoT), both of which depend heavily on extensive training data. This creates a major challenge when the amount of quality training data is scarce. We propose a sample-efficient, two-stage training strategy to develop reasoning LLMs under limited supervision. In the first stage, we "warm up" the model by distilling Long CoTs from a toy domain, namely, Knights \& Knaves (K\&K) logic puzzles to acquire general reasoning skills. In the second stage, we apply RLVR to the warmed-up model using a limited set of target-domain examples. Our experiments demonstrate that this two-phase approach offers several benefits: \\((i)\\) the warmup phase alone facilitates generalized reasoning, leading to performance improvements across a range of tasks, including MATH, HumanEval\\(^\{+\}\\), and MMLU-Pro; \\((ii)\\) When both the base model and the warmed-up model are RLVR trained on the same small dataset (\\(\leq100\\) examples), the warmed-up model consistently outperforms the base model; \\((iii)\\) Warming up before RLVR training allows a model to maintain cross-domain generalizability even after training on a specific domain; \\((iv)\\) Introducing warmup in the pipeline improves not only accuracy but also overall sample efficiency during RLVR training. The results in this paper highlight the promise of warmup for building robust reasoning LLMs in data-scarce environments.
