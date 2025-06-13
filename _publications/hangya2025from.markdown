---
layout: publication
title: 'From Understanding To Generation: An Efficient Shortcut For Evaluating Language Models'
authors: Viktor Hangya, Fabian Küch, Darina Gold
conference: "Arxiv"
year: 2025
bibkey: hangya2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03592'}
tags: ['Reinforcement Learning', 'RAG', 'Applications', 'Training Techniques']
---
Iterative evaluation of LLMs during training is essential to ensure expected capability development, but can be time- and compute-intensive. While NLU tasks, where the model selects from fixed answer choices, are cheap to evaluate, essential capabilities like reasoning and code generation rely on the more time-consuming NLG (token-by-token generation) format. In this work, our aim is to decrease the computational burden of NLG benchmarks in order to enable monitoring crucial LLM capabilities during model training. We reformulate generative tasks into computationally cheaper NLU alternatives. We test the performance correlation between the original and reformulated tasks using 8 LMs of various sizes and 4 capabilities: mathematical reasoning, code generation, factual knowledge and reading comprehension. Our results show a strong correlation between task formats, supporting capability assessment via cheaper alternatives and achieving over 35x average reduction in evaluation time. We plan to publish our benchmark adaptions.
