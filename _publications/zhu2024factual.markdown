---
layout: publication
title: 'Factual Dialogue Summarization Via Learning From Large Language Models'
authors: Rongxin Zhu, Jey Han Lau, Jianzhong Qi
conference: "Arxiv"
year: 2024
bibkey: zhu2024factual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14709"}
tags: ['Distillation', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning']
---
Factual consistency is an important quality in dialogue summarization. Large
language model (LLM)-based automatic text summarization models generate more
factually consistent summaries compared to those by smaller pretrained language
models, but they face deployment challenges in real-world applications due to
privacy or resource constraints. In this paper, we investigate the use of
symbolic knowledge distillation to improve the factual consistency of smaller
pretrained models for dialogue summarization. We employ zero-shot learning to
extract symbolic knowledge from LLMs, generating both factually consistent
(positive) and inconsistent (negative) summaries. We then apply two contrastive
learning objectives on these summaries to enhance smaller summarization models.
Experiments with BART, PEGASUS, and Flan-T5 indicate that our approach
surpasses strong baselines that rely on complex data augmentation strategies.
Our approach achieves better factual consistency while maintaining coherence,
fluency, and relevance, as confirmed by various automatic evaluation metrics.
We also provide access to the data and code to facilitate future research.
