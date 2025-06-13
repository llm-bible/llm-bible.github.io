---
layout: publication
title: 'A Flexible Large Language Models Guardrail Development Methodology Applied To Off-topic Prompt Detection'
authors: Gabriel Chua, Shing Yee Chan, Shaun Khoo
conference: "Arxiv"
year: 2024
bibkey: chua2024flexible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.12946'}
tags: ['Reinforcement Learning', 'Prompting', 'Responsible AI']
---
Large Language Models (LLMs) are prone to off-topic misuse, where users may
prompt these models to perform tasks beyond their intended scope. Current
guardrails, which often rely on curated examples or custom classifiers, suffer
from high false-positive rates, limited adaptability, and the impracticality of
requiring real-world data that is not available in pre-production. In this
paper, we introduce a flexible, data-free guardrail development methodology
that addresses these challenges. By thoroughly defining the problem space
qualitatively and passing this to an LLM to generate diverse prompts, we
construct a synthetic dataset to benchmark and train off-topic guardrails that
outperform heuristic approaches. Additionally, by framing the task as
classifying whether the user prompt is relevant with respect to the system
prompt, our guardrails effectively generalize to other misuse categories,
including jailbreak and harmful prompts. Lastly, we further contribute to the
field by open-sourcing both the synthetic dataset and the off-topic guardrail
models, providing valuable resources for developing guardrails in
pre-production environments and supporting future research and development in
LLM safety.
