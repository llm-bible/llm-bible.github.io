---
layout: publication
title: 'Comparing Retrieval-augmentation And Parameter-efficient Fine-tuning For Privacy-preserving Personalization Of Large Language Models'
authors: Alireza Salemi, Hamed Zamani
conference: "Arxiv"
year: 2024
bibkey: salemi2024comparing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.09510'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Privacy-preserving methods for personalizing large language models (LLMs) are
relatively under-explored. There are two schools of thought on this topic: (1)
generating personalized outputs by personalizing the input prompt through
retrieval augmentation from the user's personal information (RAG-based
methods), and (2) parameter-efficient fine-tuning of LLMs per user that
considers efficiency and space limitations (PEFT-based methods). This paper
presents the first systematic comparison between two approaches on a wide range
of personalization tasks using seven diverse datasets. Our results indicate
that RAG-based and PEFT-based personalization methods on average yield 14.92%
and 1.07% improvements over the non-personalized LLM, respectively. We find
that combining RAG with PEFT elevates these improvements to 15.98%.
Additionally, we identify a positive correlation between the amount of user
data and PEFT's effectiveness, indicating that RAG is a better choice for
cold-start users (i.e., user's with limited personal data).
