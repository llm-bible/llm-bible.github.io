---
layout: publication
title: 'Towards Robust Dialogue Breakdown Detection: Addressing Disruptors In Large Language Models With Self-guided Reasoning'
authors: Abdellah Ghassel, Xianzhi Li, Xiaodan Zhu
conference: "Arxiv"
year: 2025
bibkey: ghassel2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18839"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting']
---
Large language models (LLMs) are rapidly changing various domains. However,
their capabilities in handling conversational breakdowns still require an
in-depth exploration. This paper addresses the challenge of detecting and
mitigating dialogue breakdowns within LLM-driven conversational systems. While
powerful models from OpenAI and Anthropic excel in many dialogue tasks, they
can still produce incoherent or contradictory responses, commonly referred to
as breakdowns, which undermine user trust. To tackle this, we propose an
approach that combines specialized fine-tuning with advanced prompting
strategies, including few-shot learning, chain-of-thought reasoning, and
analogical prompting. In particular, we fine-tune a small 8B model and
demonstrate its robust classification and calibration capabilities in English
and Japanese dialogue. We also validate its generalization on the BETOLD
dataset, achieving a 7% accuracy improvement over its base model. Furthermore,
we introduce a real-time deployment architecture that selectively escalates
suspicious responses to more resource-intensive frontier models only when
breakdowns are detected, significantly cutting operational expenses and energy
consumption. Experimental results show our method surpasses prior
state-of-the-art specialized classifiers while also narrowing performance gaps
between smaller open-source models and large proprietary ones. Our approach
offers a scalable solution for robust conversational AI in high-impact domains
by combining efficiency, interpretability, and reliability.
