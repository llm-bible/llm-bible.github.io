---
layout: publication
title: 'Token-hungry, Yet Precise: Deepseek R1 Highlights The Need For Multi-step Reasoning Over Speed In MATH'
authors: Evgenii Evstafev
conference: "Arxiv"
year: 2025
bibkey: evstafev2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18576"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Applications']
---
This study investigates the performance of the DeepSeek R1 language model on
30 challenging mathematical problems derived from the MATH dataset, problems
that previously proved unsolvable by other models under time constraints.
Unlike prior work, this research removes time limitations to explore whether
DeepSeek R1's architecture, known for its reliance on token-based reasoning,
can achieve accurate solutions through a multi-step process. The study compares
DeepSeek R1 with four other models (gemini-1.5-flash-8b,
gpt-4o-mini-2024-07-18, llama3.1:8b, and mistral-8b-latest) across 11
temperature settings. Results demonstrate that DeepSeek R1 achieves superior
accuracy on these complex problems but generates significantly more tokens than
other models, confirming its token-intensive approach. The findings highlight a
trade-off between accuracy and efficiency in mathematical problem-solving with
large language models: while DeepSeek R1 excels in accuracy, its reliance on
extensive token generation may not be optimal for applications requiring rapid
responses. The study underscores the importance of considering task-specific
requirements when selecting an LLM and emphasizes the role of temperature
settings in optimizing performance.
