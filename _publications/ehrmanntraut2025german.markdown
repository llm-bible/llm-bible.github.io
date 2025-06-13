---
layout: publication
title: 'Moderngbert: German-only 1B Encoder Model Trained From Scratch'
authors: Anton Ehrmanntraut, Julia Wunderle, Jan Pfister, Fotis Jannidis, Andreas Hotho
conference: "Arxiv"
year: 2025
bibkey: ehrmanntraut2025german
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13136"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'BERT', 'Applications']
---
Despite the prominence of decoder-only language models, encoders remain crucial for resource-constrained applications. We introduce ModernGBERT (134M, 1B), a fully transparent family of German encoder models trained from scratch, incorporating architectural innovations from ModernBERT. To evaluate the practical trade-offs of training encoders from scratch, we also present LL\"aMmlein2Vec (120M, 1B, 7B), a family of encoders derived from German decoder-only models via LLM2Vec. We benchmark all models on natural language understanding, text embedding, and long-context reasoning tasks, enabling a controlled comparison between dedicated encoders and converted decoders. Our results show that ModernGBERT 1B outperforms prior state-of-the-art German encoders as well as encoders adapted via LLM2Vec, with regard to performance and parameter-efficiency. All models, training data, checkpoints and code are publicly available, advancing the German NLP ecosystem with transparent, high-performance encoder models.
