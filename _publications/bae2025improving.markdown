---
layout: publication
title: 'SALAD: Improving Robustness And Generalization Through Contrastive Learning With Structure-aware And Llm-driven Augmented Data'
authors: Suyoung Bae, Hyojun Kim, Yunseok Choi, Jee-hyong Lee
conference: "Arxiv"
year: 2025
bibkey: bae2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12185'}
tags: ['RAG', 'Security', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
In various natural language processing (NLP) tasks, fine-tuning Pre-trained
Language Models (PLMs) often leads to the issue of spurious correlations, which
negatively impacts performance, particularly when dealing with
out-of-distribution data. To address this problem, we propose SALAD\}(Structure
Aware and LLM-driven Augmented Data), a novel approach designed to enhance
model robustness and generalization by generating structure-aware and
counterfactually augmented data for contrastive learning. Our method leverages
a tagging-based approach to generate structure-aware positive samples and
utilizes large language models (LLMs) to generate counterfactual negative
samples with diverse sentence patterns. By applying contrastive learning, SALAD
enables the model to focus on learning the structural relationships between key
sentence components while minimizing reliance on spurious correlations. We
validate our approach through experiments on three tasks: Sentiment
Classification, Sexism Detection, and Natural Language Inference. The results
demonstrate that SALAD not only improves model robustness and performance
across different environments but also enhances generalization to
out-of-distribution datasets and cross-domain scenarios.
