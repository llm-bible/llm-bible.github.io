---
layout: publication
title: 'Autellix: An Efficient Serving Engine For LLM Agents As General Programs'
authors: Michael Luo, Xiaoxiang Shi, Colin Cai, Tianjun Zhang, Justin Wong, Yichuan Wang, Chi Wang, Yanping Huang, Zhifeng Chen, Joseph E. Gonzalez, Ion Stoica
conference: "Arxiv"
year: 2025
bibkey: luo2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13965'}
tags: ['Reinforcement Learning', 'Agentic', 'Efficiency and Optimization', 'Applications']
---
Large language model (LLM) applications are evolving beyond simple chatbots
into dynamic, general-purpose agentic programs, which scale LLM calls and
output tokens to help AI agents reason, explore, and solve complex tasks.
However, existing LLM serving systems ignore dependencies between programs and
calls, missing significant opportunities for optimization. Our analysis reveals
that programs submitted to LLM serving engines experience long cumulative wait
times, primarily due to head-of-line blocking at both the individual LLM
request and the program. To address this, we introduce Autellix, an LLM serving
system that treats programs as first-class citizens to minimize their
end-to-end latencies. Autellix intercepts LLM calls submitted by programs,
enriching schedulers with program-level context. We propose two scheduling
algorithms-for single-threaded and distributed programs-that preempt and
prioritize LLM calls based on their programs' previously completed calls. Our
evaluation demonstrates that across diverse LLMs and agentic workloads,
Autellix improves throughput of programs by 4-15x at the same latency compared
to state-of-the-art systems, such as vLLM.
