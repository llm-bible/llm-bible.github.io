---
layout: publication
title: Scaling LLM Test45;time Compute Optimally Can Be More Effective Than Scaling Model Parameters
authors: Snell Charlie, Lee Jaehoon, Xu Kelvin, Kumar Aviral
conference: "Arxiv"
year: 2024
bibkey: snell2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03314"}
tags: ['Agentic', 'Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Enabling LLMs to improve their outputs by using more test45;time computation is a critical step towards building generally self45;improving agents that can operate on open45;ended natural language. In this paper we study the scaling of inference45;time computation in LLMs with a focus on answering the question if an LLM is allowed to use a fixed but non45;trivial amount of inference45;time compute how much can it improve its performance on a challenging prompt Answering this question has implications not only on the achievable performance of LLMs but also on the future of LLM pretraining and how one should tradeoff inference45;time and pre45;training compute. Despite its importance little research attempted to understand the scaling behaviors of various test45;time inference methods. Moreover current work largely provides negative results for a number of these strategies. In this work we analyze two primary mechanisms to scale test45;time computation (1) searching against dense process45;based verifier reward models; and (2) updating the models distribution over a response adaptively given the prompt at test time. We find that in both cases the effectiveness of different approaches to scaling test45;time compute critically varies depending on the difficulty of the prompt. This observation motivates applying a compute45;optimal scaling strategy which acts to most effectively allocate test45;time compute adaptively per prompt. Using this compute45;optimal strategy we can improve the efficiency of test45;time compute scaling by more than 4x compared to a best45;of45;N baseline. Additionally in a FLOPs45;matched evaluation we find that on problems where a smaller base model attains somewhat non45;trivial success rates test45;time compute can be used to outperform a 14x larger model.
