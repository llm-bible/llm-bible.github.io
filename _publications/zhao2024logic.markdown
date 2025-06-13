---
layout: publication
title: 'LANE: Logic Alignment Of Non-tuning Large Language Models And Online Recommendation Systems For Explainable Reason Generation'
authors: Hongke Zhao, Songming Zheng, Likang Wu, Bowen Yu, Jing Wang
conference: "Arxiv"
year: 2024
bibkey: zhao2024logic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02833"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting', 'Attention Mechanism']
---
The explainability of recommendation systems is crucial for enhancing user
trust and satisfaction. Leveraging large language models (LLMs) offers new
opportunities for comprehensive recommendation logic generation. However, in
existing related studies, fine-tuning LLM models for recommendation tasks
incurs high computational costs and alignment issues with existing systems,
limiting the application potential of proven proprietary/closed-source LLM
models, such as GPT-4. In this work, our proposed effective strategy LANE
aligns LLMs with online recommendation systems without additional LLMs tuning,
reducing costs and improving explainability. This innovative approach addresses
key challenges in integrating language models with recommendation systems while
fully utilizing the capabilities of powerful proprietary models. Specifically,
our strategy operates through several key components: semantic embedding, user
multi-preference extraction using zero-shot prompting, semantic alignment, and
explainable recommendation generation using Chain of Thought (CoT) prompting.
By embedding item titles instead of IDs and utilizing multi-head attention
mechanisms, our approach aligns the semantic features of user preferences with
those of candidate items, ensuring coherent and user-aligned recommendations.
Sufficient experimental results including performance comparison, questionnaire
voting, and visualization cases prove that our method can not only ensure
recommendation performance, but also provide easy-to-understand and reasonable
recommendation logic.
