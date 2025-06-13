---
layout: publication
title: 'Echolm: Accelerating LLM Serving With Real-time Knowledge Distillation'
authors: Yifan Yu, Yu Gan, Lillian Tsai, Nikhil Sarda, Jiaming Shen, Yanqi Zhou, Arvind Krishnamurthy, Fan Lai, Henry M. Levy, David Culler
conference: "Arxiv"
year: 2025
bibkey: yu2025accelerating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.12689'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have excelled in various applications, yet
serving them at scale is challenging due to their substantial resource demands
and high latency. Our real-world studies reveal that over 60% of user requests
to LLMs have semantically similar counterparts, suggesting the potential for
knowledge sharing among requests. However, naively caching and reusing past
responses leads to large quality degradation. In this paper, we introduce
EchoLM, an in-context caching system that leverages historical requests as
examples to guide response generation, enabling selective offloading of
requests to more efficient LLMs. However, enabling this real-time knowledge
transfer leads to intricate tradeoffs between response quality, latency, and
system throughput at scale. For a new request, EchoLM identifies similar,
high-utility examples and efficiently prepends them to the input for better
response. At scale, EchoLM adaptively routes requests to LLMs of varying
capabilities, accounting for response quality and serving loads. EchoLM employs
a cost-aware cache replay mechanism to improve example quality and coverage
offline, maximizing cache utility and runtime efficiency. Evaluations on
millions of open-source requests demonstrate that EchoLM has a throughput
improvement of 1.4-5.9x while reducing latency by 28-71% without hurting
response quality on average.
