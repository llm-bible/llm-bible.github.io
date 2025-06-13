---
layout: publication
title: 'Log-augmented Generation: Scaling Test-time Reasoning With Reusable Computation'
authors: Peter Baile Chen, Yi Zhang, Dan Roth, Samuel Madden, Jacob Andreas, Michael Cafarella
conference: "Arxiv"
year: 2025
bibkey: chen2025log
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14398"}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Tools']
---
While humans naturally learn and adapt from past experiences, large language models (LLMs) and their agentic counterparts struggle to retain reasoning from previous tasks and apply them in future contexts. To address this limitation, we propose a novel framework, log-augmented generation (LAG) that directly reuses prior computation and reasoning from past logs at test time to enhance model's ability to learn from previous tasks and perform better on new, unseen challenges, all while keeping the system efficient and scalable. Specifically, our system represents task logs using key-value (KV) caches, encoding the full reasoning context of prior tasks while storing KV caches for only a selected subset of tokens. When a new task arises, LAG retrieves the KV values from relevant logs to augment generation. Our approach differs from reflection-based memory mechanisms by directly reusing prior reasoning and computations without requiring additional steps for knowledge extraction or distillation. Our method also goes beyond existing KV caching techniques, which primarily target efficiency gains rather than improving accuracy. Experiments on knowledge- and reasoning-intensive datasets demonstrate that our method significantly outperforms standard agentic systems that do not utilize logs, as well as existing solutions based on reflection and KV cache techniques.
