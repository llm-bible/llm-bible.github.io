---
layout: publication
title: 'On Designing Effective RL Reward At Training Time For LLM Reasoning'
authors: Jiaxuan Gao, Shusheng Xu, Wenjie Ye, Weilin Liu, Chuyi He, Wei Fu, Zhiyu Mei, Guangju Wang, Yi Wu
conference: "Arxiv"
year: 2024
bibkey: gao2024designing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15115"}
tags: ['Training Techniques', 'Reinforcement Learning']
---
Reward models have been increasingly critical for improving the reasoning
capability of LLMs. Existing research has shown that a well-trained reward
model can substantially improve model performances at inference time via
search. However, the potential of reward models during RL training time still
remains largely under-explored. It is currently unclear whether these reward
models can provide additional training signals to enhance the reasoning
capabilities of LLMs in RL training that uses sparse success rewards, which
verify the correctness of solutions. In this work, we evaluate popular reward
models for RL training, including the Outcome-supervised Reward Model (ORM) and
the Process-supervised Reward Model (PRM), and train a collection of LLMs for
math problems using RL by combining these learned rewards with success rewards.
Surprisingly, even though these learned reward models have strong
inference-time performances, they may NOT help or even hurt RL training,
producing worse performances than LLMs trained with the success reward only.
Our analysis reveals that an LLM can receive high rewards from some of these
reward models by repeating correct but unnecessary reasoning steps, leading to
a severe reward hacking issue. Therefore, we introduce two novel reward
refinement techniques, including Clipping and Delta. The key idea is to ensure
the accumulative reward of any reasoning trajectory is upper-bounded to keep a
learned reward model effective without being exploited. We evaluate our
techniques with multiple reward models over a set of 1.5B and 7B LLMs on MATH
and GSM8K benchmarks and demonstrate that with a carefully designed reward
function, RL training without any additional supervised tuning can improve all
the evaluated LLMs, including the state-of-the-art 7B LLM
Qwen2.5-Math-7B-Instruct on MATH and GSM8K benchmarks.
