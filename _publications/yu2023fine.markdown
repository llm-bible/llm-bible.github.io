---
layout: publication
title: 'Fine-tuning Language Models With Generative Adversarial Reward Modelling'
authors: Zhang Ze Yu, Lau Jia Jaw, Zhang Hui, Bryan Kian Hsiang Low
conference: "Arxiv"
year: 2023
bibkey: yu2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.06176"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Reinforcement Learning with Human Feedback (RLHF) has been demonstrated to
significantly enhance the performance of large language models (LLMs) by
aligning their outputs with desired human values through instruction tuning.
However, RLHF is constrained by the expertise and productivity limitations of
human evaluators. A response to this downside is to fall back to supervised
fine-tuning (SFT) with additional carefully selected expert demonstrations.
However, while this method has been proven to be effective, it invariably also
leads to increased human-in-the-loop overhead. In this study, we propose
another alternative approach: Reinforcement Learning with Generative
Adversarial Feedback (RLGAF) to RLHF and SFT, which uses a generative
adversarial training style to enable the LLMs to learn useful human expert
demonstrations without being directly exposed to the training examples, thus
enabling good generalization capabilities while preserving sample efficiency.
Our preliminary findings indicate that RLGAF can help align LLMs outputs with
competitive performance against RLHF and SFT, while not suffering from their
respective inherent restrictions, suggesting promising avenues for further
research on automating AI alignment.
