---
layout: publication
title: Optimizing Large Language Models For Openapi Code Completion
authors: Petryshyn Bohdan, Lukoševičius Mantas
conference: "Arxiv"
year: 2024
bibkey: petryshyn2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15729"}
tags: ['Applications', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent advancements in Large Language Models (LLMs) and their utilization in code generation tasks have significantly reshaped the field of software development. Despite the remarkable efficacy of code completion solutions in mainstream programming languages their performance lags when applied to less ubiquitous formats such as OpenAPI definitions. This study evaluates the OpenAPI completion performance of GitHub Copilot a prevalent commercial code completion tool and proposes a set of task45;specific optimizations leveraging Metas open45;source model Code Llama. A semantics45;aware OpenAPI completion benchmark proposed in this research is used to perform a series of experiments through which the impact of various prompt45;engineering and fine45;tuning techniques on the Code Llama models performance is analyzed. The fine45;tuned Code Llama model reaches a peak correctness improvement of 55.237; over GitHub Copilot despite utilizing 25 times fewer parameters than the commercial solutions underlying Codex model. Additionally this research proposes an enhancement to a widely used code infilling training technique addressing the issue of underperformance when the model is prompted with context sizes smaller than those used during training. The dataset the benchmark and the model fine45;tuning code are made publicly available.
