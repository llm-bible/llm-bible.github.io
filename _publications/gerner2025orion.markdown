---
layout: publication
title: 'ORION Grounded In Context: Retrieval-based Method For Hallucination Detection'
authors: Assaf Gerner, Netta Madvil, Nadav Barak, Alex Zaikman, Jonatan Liberman, Liron Hamra, Rotem Brazilay, Shay Tsadok, Yaron Friedman, Neal Harow, Noam Bressler, Shir Chorev, Philip Tannor
conference: "Arxiv"
year: 2025
bibkey: gerner2025orion
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.15771'}
tags: ['RAG', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning']
---
Despite advancements in grounded content generation, production Large Language Models (LLMs) based applications still suffer from hallucinated answers. We present "Grounded in Context" - a member of Deepchecks' ORION (Output Reasoning-based InspectiON) family of lightweight evaluation models. It is our framework for hallucination detection, designed for production-scale long-context data and tailored to diverse use cases, including summarization, data extraction, and RAG. Inspired by RAG architecture, our method integrates retrieval and Natural Language Inference (NLI) models to predict factual consistency between premises and hypotheses using an encoder-based model with only a 512-token context window. Our framework identifies unsupported claims with an F1 score of 0.83 in RAGTruth's response-level classification task, matching methods that trained on the dataset, and outperforming all comparable frameworks using similar-sized models.
