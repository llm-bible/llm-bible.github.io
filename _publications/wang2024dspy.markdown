---
layout: publication
title: 'Dspy-based Neural-symbolic Pipeline To Enhance Spatial Reasoning In Llms'
authors: Rong Wang, Kun Sun, Jonas Kuhn
conference: "Arxiv"
year: 2024
bibkey: wang2024dspy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.18564'}
tags: ['RAG', 'Model Architecture', 'Tools', 'GPT', 'Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
various tasks, yet they often struggle with spatial reasoning. This paper
presents a novel neural-symbolic framework that enhances LLMs' spatial
reasoning abilities through iterative feedback between LLMs and Answer Set
Programming (ASP). We evaluate our approach on two benchmark datasets: StepGame
and SparQA, implementing three distinct strategies: (1) direct prompting
baseline, (2) Facts+Rules prompting, and (3) DSPy-based LLM+ASP pipeline with
iterative refinement. Our experimental results demonstrate that the LLM+ASP
pipeline significantly outperforms baseline methods, achieving an average 82%
accuracy on StepGame and 69% on SparQA, marking improvements of 40-50% and
8-15% respectively over direct prompting. The success stems from three key
innovations: (1) effective separation of semantic parsing and logical reasoning
through a modular pipeline, (2) iterative feedback mechanism between LLMs and
ASP solvers that improves program rate, and (3) robust error handling that
addresses parsing, grounding, and solving failures. Additionally, we propose
Facts+Rules as a lightweight alternative that achieves comparable performance
on complex SparQA dataset, while reducing computational overhead.Our analysis
across different LLM architectures (Deepseek, Llama3-70B, GPT-4.0 mini)
demonstrates the framework's generalizability and provides insights into the
trade-offs between implementation complexity and reasoning capability,
contributing to the development of more interpretable and reliable AI systems.
