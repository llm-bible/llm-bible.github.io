---
layout: publication
title: 'Verbalized Confidence Triggers Self-verification: Emergent Behavior Without Explicit Reasoning Supervision'
authors: Chaeyun Jang, Moonseok Choi, Yegon Kim, Hyungi Lee, Juho Lee
conference: "Arxiv"
year: 2025
bibkey: jang2025verbalized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03723'}
tags: ['Agentic', 'Interpretability and Explainability', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Uncertainty calibration is essential for the safe deployment of large language models (LLMs), particularly when users rely on verbalized confidence estimates. While prior work has focused on classifiers or short-form generation, confidence calibration for chain-of-thought (CoT) reasoning remains largely unexplored. Surprisingly, we find that supervised fine-tuning with scalar confidence labels alone suffices to elicit self-verification behavior of language models, without any explicit reasoning supervision or reinforcement learning-based rewards. Despite being trained only to produce a verbalized confidence score without any self-verifying examples, the model learns to generate longer and self-checking responses for low-confidence queries while providing more concise answers for high-confidence ones. We further propose a simple rethinking method that boosts performance via test-time scaling based on calibrated uncertainty. Experiments on GSM8K and held-out reasoning tasks such as MATH-500 and ARC-Challenge show that our confidence-aware fine-tuning improves both calibration and accuracy, while also enhancing interpretability by aligning the model's reasoning path with its confidence.
