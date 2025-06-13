---
layout: publication
title: 'Explainability-based Token Replacement On Llm-generated Text'
authors: Hadi Mohammadi, Anastasia Giachanou, Daniel L. Oberski, Ayoub Bagheri
conference: "Arxiv"
year: 2025
bibkey: mohammadi2025explainability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04050"}
tags: ['Interpretability', 'Training Techniques', 'Interpretability and Explainability']
---
Generative models, especially large language models (LLMs), have shown remarkable progress in producing text that appears human-like. However, they often exhibit patterns that make their output easier to detect than text written by humans. In this paper, we investigate how explainable AI (XAI) methods can be used to reduce the detectability of AI-generated text (AIGT) while also introducing a robust ensemble-based detection approach. We begin by training an ensemble classifier to distinguish AIGT from human-written text, then apply SHAP and LIME to identify tokens that most strongly influence its predictions. We propose four explainability-based token replacement strategies to modify these influential tokens. Our findings show that these token replacement approaches can significantly diminish a single classifier's ability to detect AIGT. However, our ensemble classifier maintains strong performance across multiple languages and domains, showing that a multi-model approach can mitigate the impact of token-level manipulations. These results show that XAI methods can make AIGT harder to detect by focusing on the most influential tokens. At the same time, they highlight the need for robust, ensemble-based detection strategies that can adapt to evolving approaches for hiding AIGT.
