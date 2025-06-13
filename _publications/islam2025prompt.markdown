---
layout: publication
title: 'Prompt-based Llms For Position Bias-aware Reranking In Personalized Recommendations'
authors: Md Aminul Islam, Ahmed Sayeed Faruk
conference: "Arxiv"
year: 2025
bibkey: islam2025prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04948'}
  - {name: "Code", url: 'https://github.com/aminul7506/LLMForReRanking'}
tags: ['Has Code', 'Training Techniques', 'Tools', 'Prompting', 'RecSys', 'Reinforcement Learning', 'Ethics and Bias']
---
Recommender systems are essential for delivering personalized content across digital platforms by modeling user preferences and behaviors. Recently, large language models (LLMs) have been adopted for prompt-based recommendation due to their ability to generate personalized outputs without task-specific training. However, LLM-based methods face limitations such as limited context window size, inefficient pointwise and pairwise prompting, and difficulty handling listwise ranking due to token constraints. LLMs can also be sensitive to position bias, as they may overemphasize earlier items in the prompt regardless of their true relevance. To address and investigate these issues, we propose a hybrid framework that combines a traditional recommendation model with an LLM for reranking top-k items using structured prompts. We evaluate the effects of user history reordering and instructional prompts for mitigating position bias. Experiments on MovieLens-100K show that randomizing user history improves ranking quality, but LLM-based reranking does not outperform the base model. Explicit instructions to reduce position bias are also ineffective. Our evaluations reveal limitations in LLMs' ability to model ranking context and mitigate bias. Our code is publicly available at https://github.com/aminul7506/LLMForReRanking.
