---
layout: publication
title: 'Detecting Prefix Bias In Llm-based Reward Models'
authors: Ashwin Kumar, Yuzi He, Aram H. Markosyan, Bobbie Chern, Imanol Arrieta-ibarra
conference: "Arxiv"
year: 2025
bibkey: kumar2025detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13487"}
tags: ['Agentic', 'Model Architecture', 'Fairness', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
Reinforcement Learning with Human Feedback (RLHF) has emerged as a key paradigm for task-specific fine-tuning of language models using human preference data. While numerous publicly available preference datasets provide pairwise comparisons of responses, the potential for biases in the resulting reward models remains underexplored. In this work, we introduce novel methods to detect and evaluate prefix bias -- a systematic shift in model preferences triggered by minor variations in query prefixes -- in LLM-based reward models trained on such datasets. We leverage these metrics to reveal significant biases in preference models across racial and gender dimensions. Our comprehensive evaluation spans diverse open-source preference datasets and reward model architectures, demonstrating susceptibility to this kind of bias regardless of the underlying model architecture. Furthermore, we propose a data augmentation strategy to mitigate these biases, showing its effectiveness in reducing the impact of prefix bias. Our findings highlight the critical need for bias-aware dataset design and evaluation in developing fair and reliable reward models, contributing to the broader discourse on fairness in AI.
