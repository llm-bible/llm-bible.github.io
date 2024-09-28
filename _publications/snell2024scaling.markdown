---
layout: publication
title: Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters
authors: Snell Charlie, Lee Jaehoon, Xu Kelvin, Kumar Aviral
conference: "Arxiv"
year: 2024
bibkey: snell2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03314"}
tags: ['ARXIV', 'Agent', 'LLM', 'Pretraining Methods', 'Prompt']
---
Enabling LLMs to improve their outputs by using more test-time computation is a critical step towards building generally self-improving agents that can operate on open-ended natural language. In this paper we study the scaling of inference-time computation in LLMs with a focus on answering the question if an LLM is allowed to use a fixed but non-trivial amount of inference-time compute how much can it improve its performance on a challenging prompt Answering this question has implications not only on the achievable performance of LLMs but also on the future of LLM pretraining and how one should tradeoff inference-time and pre-training compute. Despite its importance little research attempted to understand the scaling behaviors of various test-time inference methods. Moreover current work largely provides negative results for a number of these strategies. In this work we analyze two primary mechanisms to scale test-time computation (1) searching against dense process-based verifier reward models; and (2) updating the models distribution over a response adaptively given the prompt at test time. We find that in both cases the effectiveness of different approaches to scaling test-time compute critically varies depending on the difficulty of the prompt. This observation motivates applying a compute-optimal scaling strategy which acts to most effectively allocate test-time compute adaptively per prompt. Using this compute-optimal strategy we can improve the efficiency of test-time compute scaling by more than 4x compared to a best-of-N baseline. Additionally in a FLOPs-matched evaluation we find that on problems where a smaller base model attains somewhat non-trivial success rates test-time compute can be used to outperform a 14x larger model.
