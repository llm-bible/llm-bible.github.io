---
layout: publication
title: 'Valuesrag: Enhancing Cultural Alignment Through Retrieval-augmented Contextual Learning'
authors: Wonduk Seo, Zonghao Yuan, Yi Bu
conference: "Arxiv"
year: 2025
bibkey: seo2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01031"}
tags: ['Training Techniques', 'Fairness', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'Survey Paper', 'RAG', 'Language Modeling', 'Bias Mitigation', 'Ethics and Bias', 'Prompting', 'Applications', 'In-Context Learning']
---
Ensuring cultural values alignment in Large Language Models (LLMs) remains a
critical challenge, as these models often embed Western-centric biases from
their training data, leading to misrepresentations and fairness concerns in
cross-cultural applications. Existing approaches such as role assignment and
few-shot learning struggle to address these limitations effectively due to
their reliance on pre-trained knowledge, limited scalability, and inability to
capture nuanced cultural values. To address these issues, we propose ValuesRAG,
a novel and effective framework that applies Retrieval-Augmented Generation
(RAG) with In-Context Learning (ICL) to integrate cultural and demographic
knowledge dynamically during text generation. Leveraging the World Values
Survey (WVS) dataset, ValuesRAG first generates summaries of values for each
individual. We subsequently curate several representative regional datasets to
serve as test datasets and retrieve relevant summaries of values based on
demographic features, followed by a reranking step to select the top-k relevant
summaries. We evaluate ValuesRAG using 6 diverse regional datasets and show
that it consistently outperforms baselines: including zero-shot,
role-assignment, few-shot, and hybrid methods, both in main experiments and
ablation settings. Notably, ValuesRAG achieves the best overall performance
over prior methods, demonstrating its effectiveness in fostering culturally
aligned and inclusive AI systems. Our findings underscore the potential of
dynamic retrieval-based methods to bridge the gap between global LLM
capabilities and localized cultural values.
