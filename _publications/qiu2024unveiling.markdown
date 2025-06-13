---
layout: publication
title: 'Unveiling User Preferences: A Knowledge Graph And Llm-driven Approach For Conversational Recommendation'
authors: Zhangchi Qiu, Linhao Luo, Shirui Pan, Alan Wee-chung Liew
conference: "Arxiv"
year: 2024
bibkey: qiu2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14459"}
tags: ['Training Techniques', 'Tools', 'RecSys', 'Ethics and Bias', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Pre-Training', 'Applications']
---
Conversational Recommender Systems (CRSs) aim to provide personalized
recommendations through dynamically capturing user preferences in interactive
conversations. Conventional CRSs often extract user preferences as hidden
representations, which are criticized for their lack of interpretability. This
diminishes the transparency and trustworthiness of the recommendation process.
Recent works have explored combining the impressive capabilities of Large
Language Models (LLMs) with the domain-specific knowledge of Knowledge Graphs
(KGs) to generate human-understandable recommendation explanations. Despite
these efforts, the integration of LLMs and KGs for CRSs remains challenging due
to the modality gap between unstructured dialogues and structured KGs.
Moreover, LLMs pre-trained on large-scale corpora may not be well-suited for
analyzing user preferences, which require domain-specific knowledge. In this
paper, we propose COMPASS, a plug-and-play framework that synergizes LLMs and
KGs to unveil user preferences, enhancing the performance and explainability of
existing CRSs. To address integration challenges, COMPASS employs a two-stage
training approach: first, it bridges the gap between the structured KG and
natural language through an innovative graph entity captioning pre-training
mechanism. This enables the LLM to transform KG entities into concise natural
language descriptions, allowing them to comprehend domain-specific knowledge.
Following, COMPASS optimizes user preference modeling via knowledge-aware
instruction fine-tuning, where the LLM learns to reason and summarize user
preferences from both dialogue histories and KG-augmented context. This enables
COMPASS to perform knowledge-aware reasoning and generate comprehensive and
interpretable user preferences that can seamlessly integrate with existing CRS
models for improving recommendation performance and explainability.
