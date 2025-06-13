---
layout: publication
title: 'Rethinking Llm-based Recommendations: A Query Generation-based, Training-free Approach'
authors: Donghee Han, Hwanjun Song, Mun Yong Yi
conference: "Arxiv"
year: 2025
bibkey: han2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11889"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Prompting']
---
Existing large language model LLM-based recommendation methods face several
challenges, including inefficiency in handling large candidate pools,
sensitivity to item order within prompts ("lost in the middle" phenomenon) poor
scalability, and unrealistic evaluation due to random negative sampling. To
address these issues, we propose a Query-to-Recommendation approach that
leverages LLMs to generate personalized queries for retrieving relevant items
from the entire candidate pool, eliminating the need for candidate
pre-selection. This method can be integrated into an ID-based recommendation
system without additional training, enhances recommendation performance and
diversity through LLMs' world knowledge, and performs well even for less
popular item groups. Experiments on three datasets show up to 57 percent
improvement, with an average gain of 31 percent, demonstrating strong zero-shot
performance and further gains when ensembled with existing models.
