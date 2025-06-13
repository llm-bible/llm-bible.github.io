---
layout: publication
title: 'A Lightweight Method To Disrupt Memorized Sequences In LLM'
authors: Parjanya Prajakta Prashant, Kaustubh Ponkshe, Babak Salimi
conference: "Arxiv"
year: 2025
bibkey: prashant2025lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05159"}
tags: ['Responsible AI', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
As language models scale, their performance improves dramatically across a wide range of tasks, but so does their tendency to memorize and regurgitate parts of their training data verbatim. This tradeoff poses serious legal, ethical, and safety concerns, especially in real-world deployments. Existing mitigation techniques, such as differential privacy or model unlearning, often require retraining or access to internal weights making them impractical for most users. In this work, we introduce TokenSwap, a lightweight, post-hoc defense designed for realistic settings where the user can only access token-level outputs. Our key insight is that while large models are necessary for high task performance, small models (e.g., DistilGPT-2) are often sufficient to assign fluent, grammatically plausible probabilities to common function words - and crucially, they memorize far less. By selectively swapping token probabilities between models, TokenSwap preserves the capabilities of large models while reducing their propensity for verbatim reproduction. Evaluations on Pythia-6.9B and Llama-3-8B show up to a 10\\(\times\\) drop in exact memorization with negligible task degradation. Our method offers a practical, accessible solution for mitigating memorized generation in deployed LLMs.
