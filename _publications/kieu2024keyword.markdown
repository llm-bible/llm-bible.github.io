---
layout: publication
title: 'Keyword-driven Retrieval-augmented Large Language Models For Cold-start User Recommendations'
authors: Hai-dang Kieu, Minh Duc Nguyen, Thanh-son Nguyen, Dung D. Le
conference: "Arxiv"
year: 2024
bibkey: kieu2024keyword
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.19612'}
tags: ['Few-Shot', 'RAG', 'Tools', 'Prompting', 'RecSys']
---
Recent advancements in Large Language Models (LLMs) have shown significant
potential in enhancing recommender systems. However, addressing the cold-start
recommendation problem, where users lack historical data, remains a
considerable challenge. In this paper, we introduce KALM4Rec (Keyword-driven
Retrieval-Augmented Large Language Models for Cold-start User Recommendations),
a novel framework specifically designed to tackle this problem by requiring
only a few input keywords from users in a practical scenario of cold-start user
restaurant recommendations. KALM4Rec operates in two main stages: candidates
retrieval and LLM-based candidates re-ranking. In the first stage,
keyword-driven retrieval models are used to identify potential candidates,
addressing LLMs' limitations in processing extensive tokens and reducing the
risk of generating misleading information. In the second stage, we employ LLMs
with various prompting strategies, including zero-shot and few-shot techniques,
to re-rank these candidates by integrating multiple examples directly into the
LLM prompts. Our evaluation, using a Yelp restaurant dataset with user reviews
from three English-speaking cities, shows that our proposed framework
significantly improves recommendation quality. Specifically, the integration of
in-context instructions with LLMs for re-ranking markedly enhances the
performance of the cold-start user recommender system.
