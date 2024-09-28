---
layout: publication
title: Guardrail Baselines for Unlearning in LLMs
authors: Thaker Pratiksha, Maurya Yash, Hu Shengyuan, Wu Zhiwei Steven, Smith Virginia
conference: "Arxiv"
year: 2024
bibkey: thaker2024guardrail
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03329"}
tags: ['ARXIV', 'Pretraining Methods', 'Prompt']
---
Recent work has demonstrated that finetuning is a promising approach to unlearn concepts from large language models. However finetuning can be expensive as it requires both generating a set of examples and running iterations of finetuning to update the model. In this work we show that simple guardrail-based approaches such as prompting and filtering can achieve unlearning results comparable to finetuning. We recommend that researchers investigate these lightweight baselines when evaluating the performance of more computationally intensive finetuning methods. While we do not claim that methods such as prompting or filtering are universal solutions to the problem of unlearning our work suggests the need for evaluation metrics that can better separate the power of guardrails vs. finetuning and highlights scenarios where guardrails expose possible unintended behavior in existing metrics and benchmarks.
