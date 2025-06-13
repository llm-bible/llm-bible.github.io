---
layout: publication
title: 'Benchmarking Bias In Large Language Models During Role-playing'
authors: Xinyue Li, Zhenpeng Chen, Jie M. Zhang, Yiling Lou, Tianlin Li, Weisong Sun, Yang Liu, Xuanzhe Liu
conference: "Arxiv"
year: 2024
bibkey: li2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00585"}
tags: ['Tools', 'Ethics and Bias', 'Applications', 'RAG', 'Bias Mitigation', 'Reinforcement Learning', 'Fairness', 'Prompting']
---
Large Language Models (LLMs) have become foundational in modern
language-driven applications, profoundly influencing daily life. A critical
technique in leveraging their potential is role-playing, where LLMs simulate
diverse roles to enhance their real-world utility. However, while research has
highlighted the presence of social biases in LLM outputs, it remains unclear
whether and to what extent these biases emerge during role-playing scenarios.
In this paper, we introduce BiasLens, a fairness testing framework designed to
systematically expose biases in LLMs during role-playing. Our approach uses
LLMs to generate 550 social roles across a comprehensive set of 11 demographic
attributes, producing 33,000 role-specific questions targeting various forms of
bias. These questions, spanning Yes/No, multiple-choice, and open-ended
formats, are designed to prompt LLMs to adopt specific roles and respond
accordingly. We employ a combination of rule-based and LLM-based strategies to
identify biased responses, rigorously validated through human evaluation. Using
the generated questions as the benchmark, we conduct extensive evaluations of
six advanced LLMs released by OpenAI, Mistral AI, Meta, Alibaba, and DeepSeek.
Our benchmark reveals 72,716 biased responses across the studied LLMs, with
individual models yielding between 7,754 and 16,963 biased responses,
underscoring the prevalence of bias in role-playing contexts. To support future
research, we have publicly released the benchmark, along with all scripts and
experimental results.
