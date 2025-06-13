---
layout: publication
title: 'Replay To Remember: Retaining Domain Knowledge In Streaming Language Models'
authors: Sneh University Of Massachusetts Dartmouth Pillai
conference: "Arxiv"
year: 2025
bibkey: pillai2025replay
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17780"}
tags: ['Model Architecture', 'Fine-Tuning', 'GPT', 'Reinforcement Learning']
---
Continual learning in large language models (LLMs) typically encounters the
critical challenge of catastrophic forgetting, where previously acquired
knowledge deteriorates upon exposure to new data. While techniques like replay
buffers and parameter-efficient tuning (e.g., Low-Rank Adaptation or LoRA) have
been proposed, few studies investigate real-time domain adaptation under strict
computational and data-stream constraints. In this paper, we demonstrate a
lightweight method combining LoRA and a minimal replay mechanism in a realistic
streaming setting across three diverse knowledge domains: medical question
answering, genetics, and law. Using perplexity, semantic similarity, and
GPT-based human-like evaluation metrics, we quantify the model's adaptation,
forgetting, and recovery over time. Our experiments reveal that while
catastrophic forgetting naturally occurs, even minimal replay significantly
stabilizes and partially restores domain-specific knowledge. This study
contributes practical insights for deploying adaptable LLMs in
resource-constrained, real-world scenarios.
