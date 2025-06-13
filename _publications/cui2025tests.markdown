---
layout: publication
title: 'Tests As Prompt: A Test-driven-development Benchmark For LLM Code Generation'
authors: Yi Cui
conference: "Arxiv"
year: 2025
bibkey: cui2025tests
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.09027'}
tags: ['Training Techniques', 'Applications', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
We introduce WebApp1K, a novel benchmark for evaluating large language models (LLMs) in test-driven development (TDD) tasks, where test cases serve as both prompt and verification for code generation. Unlike traditional approaches relying on natural language prompts, our benchmark emphasizes the ability of LLMs to interpret and implement functionality directly from test cases, reflecting real-world software development practices. Comprising 1000 diverse challenges across 20 application domains, the benchmark evaluates LLMs on their ability to generate compact, functional code under the constraints of context length and multi-feature complexity. Our findings highlight instruction following and in-context learning as critical capabilities for TDD success, surpassing the importance of general coding proficiency or pretraining knowledge. Through comprehensive evaluation of 19 frontier models, we reveal performance bottlenecks, such as instruction loss in long prompts, and provide a detailed error analysis spanning multiple root causes. This work underscores the practical value of TDD-specific benchmarks and lays the foundation for advancing LLM capabilities in rigorous, application-driven coding scenarios.
