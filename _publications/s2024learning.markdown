---
layout: publication
title: 'In-context Learning Demonstration Selection Via Influence Analysis'
authors: Vinay M. S., Minh-hao Van, Xintao Wu
conference: "Arxiv"
year: 2024
bibkey: s2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11750"}
tags: ['Fine-Tuning', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have showcased their In-Context Learning (ICL)
capabilities, enabling few-shot learning without the need for gradient updates.
Despite its advantages, the effectiveness of ICL heavily depends on the choice
of demonstrations. Selecting the most effective demonstrations for ICL remains
a significant research challenge. To tackle this issue, we propose a
demonstration selection method named InfICL, which utilizes influence functions
to analyze impacts of training samples. By identifying the most influential
training samples as demonstrations, InfICL aims to enhance the ICL
generalization performance. To keep InfICL cost-effective, we only use the LLM
to generate sample input embeddings, avoiding expensive fine-tuning. Through
empirical studies on various real-world datasets, we demonstrate advantages of
InfICL compared to state-of-the-art baselines.
