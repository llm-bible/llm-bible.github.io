---
layout: publication
title: 'Are You Getting What You Pay For? Auditing Model Substitution In LLM Apis'
authors: Will Cai, Tianneng Shi, Xuandong Zhao, Dawn Song
conference: "Arxiv"
year: 2025
bibkey: cai2025are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04715"}
  - {name: "Code", url: "https://github.com/sunblaze-ucb/llm-api-audit"}
tags: ['Security', 'Efficiency and Optimization', 'Fairness', 'Tools', 'Bias Mitigation', 'Quantization', 'Ethics and Bias', 'Interpretability', 'Has Code']
---
The proliferation of Large Language Models (LLMs) accessed via black-box APIs
introduces a significant trust challenge: users pay for services based on
advertised model capabilities (e.g., size, performance), but providers may
covertly substitute the specified model with a cheaper, lower-quality
alternative to reduce operational costs. This lack of transparency undermines
fairness, erodes trust, and complicates reliable benchmarking. Detecting such
substitutions is difficult due to the black-box nature, typically limiting
interaction to input-output queries. This paper formalizes the problem of model
substitution detection in LLM APIs. We systematically evaluate existing
verification techniques, including output-based statistical tests, benchmark
evaluations, and log probability analysis, under various realistic attack
scenarios like model quantization, randomized substitution, and benchmark
evasion. Our findings reveal the limitations of methods relying solely on text
outputs, especially against subtle or adaptive attacks. While log probability
analysis offers stronger guarantees when available, its accessibility is often
limited. We conclude by discussing the potential of hardware-based solutions
like Trusted Execution Environments (TEEs) as a pathway towards provable model
integrity, highlighting the trade-offs between security, performance, and
provider adoption. Code is available at
https://github.com/sunblaze-ucb/llm-api-audit
