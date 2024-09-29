---
layout: publication
title: Multilingual Prompts in LLM-Based Recommenders Performance Across Languages
authors: Ozsoy Makbule Gulcin
conference: "Arxiv"
year: 2024
bibkey: ozsoy2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07604"}
tags: ['Agentic', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) are increasingly used in natural language processing tasks. Recommender systems traditionally use methods such as collaborative filtering and matrix factorization as well as advanced techniques like deep learning and reinforcement learning. Although language models have been applied in recommendation the recent trend have focused on leveraging the generative capabilities of LLMs for more personalized suggestions. While current research focuses on English due to its resource richness this work explores the impact of non-English prompts on recommendation performance. Using OpenP5 a platform for developing and evaluating LLM-based recommendations we expanded its English prompt templates to include Spanish and Turkish. Evaluation on three real-world datasets namely ML1M LastFM and Amazon-Beauty showed that usage of non-English prompts generally reduce performance especially in less-resourced languages like Turkish. We also retrained an LLM-based recommender model with multilingual prompts to analyze performance variations. Retraining with multilingual prompts resulted in more balanced performance across languages but slightly reduced English performance. This work highlights the need for diverse language support in LLM-based recommenders and suggests future research on creating evaluation datasets using newer models and additional languages.
