---
layout: publication
title: 'Toxilab: How Well Do Open-source Llms Generate Synthetic Toxicity Data?'
authors: Zheng Hui, Zhaoxiao Guo, Hang Zhao, Juanyong Duan, Lin Ai, Yinheng Li, Julia Hirschberg, Congrui Huang
conference: "Arxiv"
year: 2024
bibkey: hui2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15175"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Effective toxic content detection relies heavily on high-quality and diverse
data, which serve as the foundation for robust content moderation models.
Synthetic data has become a common approach for training models across various
NLP tasks. However, its effectiveness remains uncertain for highly subjective
tasks like hate speech detection, with previous research yielding mixed
results. This study explores the potential of open-source LLMs for harmful data
synthesis, utilizing controlled prompting and supervised fine-tuning techniques
to enhance data quality and diversity. We systematically evaluated 6 open
source LLMs on 5 datasets, assessing their ability to generate diverse,
high-quality harmful data while minimizing hallucination and duplication. Our
results show that Mistral consistently outperforms other open models, and
supervised fine-tuning significantly enhances data reliability and diversity.
We further analyze the trade-offs between prompt-based vs. fine-tuned toxic
data synthesis, discuss real-world deployment challenges, and highlight ethical
considerations. Our findings demonstrate that fine-tuned open source LLMs
provide scalable and cost-effective solutions to augment toxic content
detection datasets, paving the way for more accessible and transparent content
moderation tools.
