---
layout: publication
title: 'Cognitive-mental-llm: Evaluating Reasoning In Large Language Models For Mental Health Prediction Via Online Text'
authors: Avinash Patil, Amardeep Kour Gedhu
conference: "Arxiv"
year: 2025
bibkey: patil2025cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10095"}
tags: ['Transformer', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Pretraining Methods', 'BERT', 'Few-Shot', 'Prompting']
---
Large Language Models (LLMs) have demonstrated potential in predicting mental
health outcomes from online text, yet traditional classification methods often
lack interpretability and robustness. This study evaluates structured reasoning
techniques-Chain-of-Thought (CoT), Self-Consistency (SC-CoT), and
Tree-of-Thought (ToT)-to improve classification accuracy across multiple mental
health datasets sourced from Reddit. We analyze reasoning-driven prompting
strategies, including Zero-shot CoT and Few-shot CoT, using key performance
metrics such as Balanced Accuracy, F1 score, and Sensitivity/Specificity. Our
findings indicate that reasoning-enhanced techniques improve classification
performance over direct prediction, particularly in complex cases. Compared to
baselines such as Zero Shot non-CoT Prompting, and fine-tuned pre-trained
transformers such as BERT and Mental-RoBerta, and fine-tuned Open Source LLMs
such as Mental Alpaca and Mental-Flan-T5, reasoning-driven LLMs yield notable
gains on datasets like Dreaddit (+0.52% over M-LLM, +0.82% over BERT) and
SDCNL (+4.67% over M-LLM, +2.17% over BERT). However, performance declines in
Depression Severity, and CSSRS predictions suggest dataset-specific
limitations, likely due to our using a more extensive test set. Among prompting
strategies, Few-shot CoT consistently outperforms others, reinforcing the
effectiveness of reasoning-driven LLMs. Nonetheless, dataset variability
highlights challenges in model reliability and interpretability. This study
provides a comprehensive benchmark of reasoning-based LLM techniques for mental
health text classification. It offers insights into their potential for
scalable clinical applications while identifying key challenges for future
improvements.
