---
layout: publication
title: Keyword45;driven Retrieval45;augmented Large Language Models For Cold45;start User Recommendations
authors: Kieu Hai-dang, Nguyen Minh Duc, Nguyen Thanh-son, Le Dung D.
conference: "Arxiv"
year: 2024
bibkey: kieu2024keyword
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19612"}
tags: ['Prompting', 'RAG', 'Tools']
---
Recent advancements in Large Language Models (LLMs) have shown significant potential in enhancing recommender systems. However addressing the cold45;start recommendation problem where users lack historical data remains a considerable challenge. In this paper we introduce KALM4Rec (Keyword45;driven Retrieval45;Augmented Large Language Models for Cold45;start User Recommendations) a novel framework specifically designed to tackle this problem by requiring only a few input keywords from users in a practical scenario of cold45;start user restaurant recommendations. KALM4Rec operates in two main stages candidates retrieval and LLM45;based candidates re45;ranking. In the first stage keyword45;driven retrieval models are used to identify potential candidates addressing LLMs limitations in processing extensive tokens and reducing the risk of generating misleading information. In the second stage we employ LLMs with various prompting strategies including zero45;shot and few45;shot techniques to re45;rank these candidates by integrating multiple examples directly into the LLM prompts. Our evaluation using a Yelp restaurant dataset with user reviews from three English45;speaking cities shows that our proposed framework significantly improves recommendation quality. Specifically the integration of in45;context instructions with LLMs for re45;ranking markedly enhances the performance of the cold45;start user recommender system.
