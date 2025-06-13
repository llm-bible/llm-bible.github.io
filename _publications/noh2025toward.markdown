---
layout: publication
title: 'Toward Responsible Federated Large Language Models: Leveraging A Safety Filter And Constitutional AI'
authors: Eunchung Noh, Jeonghun Baek
conference: "Arxiv"
year: 2025
bibkey: noh2025toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16691"}
tags: ['Responsible AI', 'RAG', 'Training Techniques', 'Ethics and Bias']
---
Recent research has increasingly focused on training large language models
(LLMs) using federated learning, known as FedLLM. However, responsible AI
(RAI), which aims to ensure safe responses, remains underexplored in the
context of FedLLM. In FedLLM, client data used for training may contain harmful
content, leading to unsafe LLMs that generate harmful responses. Aggregating
such unsafe LLMs into the global model and distributing them to clients may
result in the widespread deployment of unsafe LLMs. To address this issue, we
incorporate two well-known RAI methods into FedLLM: the safety filter and
constitutional AI. Our experiments demonstrate that these methods significantly
enhance the safety of the LLM, achieving over a 20% improvement on AdvBench, a
benchmark for evaluating safety performance.
