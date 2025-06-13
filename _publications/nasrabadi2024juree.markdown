---
layout: publication
title: 'Juree Not Judges: Safeguarding Llm Interactions With Small, Specialised Encoder Ensembles'
authors: Dom Nasrabadi
conference: "Arxiv"
year: 2024
bibkey: nasrabadi2024juree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08442"}
tags: ['Responsible AI', 'Transformer', 'Efficiency and Optimization', 'Applications', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Security', 'Pretraining Methods']
---
We introduce JurEE, an ensemble of efficient, encoder-only transformer models
designed to strengthen safeguards in AI-User interactions within LLM-based
systems. Unlike existing LLM-as-Judge methods, which often struggle with
generalization across risk taxonomies and only provide textual outputs, JurEE
offers probabilistic risk estimates across a wide range of prevalent risks. Our
approach leverages diverse data sources and employs progressive synthetic data
generation techniques, including LLM-assisted augmentation, to enhance model
robustness and performance. We create an in-house benchmark comprising of other
reputable benchmarks such as the OpenAI Moderation Dataset and ToxicChat, where
we find JurEE significantly outperforms baseline models, demonstrating superior
accuracy, speed, and cost-efficiency. This makes it particularly suitable for
applications requiring stringent content moderation, such as customer-facing
chatbots. The encoder-ensemble's modular design allows users to set tailored
risk thresholds, enhancing its versatility across various safety-related
applications. JurEE's collective decision-making process, where each
specialized encoder model contributes to the final output, not only improves
predictive accuracy but also enhances interpretability. This approach provides
a more efficient, performant, and economical alternative to traditional LLMs
for large-scale implementations requiring robust content moderation.
