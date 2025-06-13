---
layout: publication
title: 'TRIM: Token Reduction And Inference Modeling For Cost-effective Language Generation'
authors: Alfredo Garrachón Ruiz, Tomás De La Rosa, Daniel Borrajo
conference: "Arxiv"
year: 2024
bibkey: ruiz2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07682"}
tags: ['RAG', 'Efficiency and Optimization', 'Prompting', 'Reinforcement Learning']
---
The inference cost of Large Language Models (LLMs) is a significant challenge
due to their computational demands, specially on tasks requiring long outputs.
However, natural language often contains redundancy, which presents an
opportunity for optimization. We have observed that LLMs can generate distilled
language-concise outputs that retain essential meaning, when prompted
appropriately. We propose TRIM, a pipeline for saving computational cost in
which a shorter distilled output from the LLM is reconstructed into a full
narrative by a smaller model with lower inference costs. Our experiments show
promising results, particularly in general knowledge domains with 20.58% saved
tokens on average with tiny decrease in evaluation metrics, hinting that this
approach can effectively balance efficiency and accuracy in language processing
tasks.
