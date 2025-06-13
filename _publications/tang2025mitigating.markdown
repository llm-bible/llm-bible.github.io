---
layout: publication
title: 'Mitigating Hallucinated Translations In Large Language Models With Hallucination-focused Preference Optimization'
authors: Zilu Tang, Rajen Chatterjee, Sarthak Garg
conference: "NAACL 2025"
year: 2025
bibkey: tang2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17295"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Machine Translation (MT) is undergoing a paradigm shift, with systems based
on fine-tuned large language models (LLM) becoming increasingly competitive
with traditional encoder-decoder models trained specifically for translation
tasks. However, LLM-based systems are at a higher risk of generating
hallucinations, which can severely undermine user's trust and safety. Most
prior research on hallucination mitigation focuses on traditional MT models,
with solutions that involve post-hoc mitigation - detecting hallucinated
translations and re-translating them. While effective, this approach introduces
additional complexity in deploying extra tools in production and also increases
latency. To address these limitations, we propose a method that intrinsically
learns to mitigate hallucinations during the model training phase.
Specifically, we introduce a data creation framework to generate hallucination
focused preference datasets. Fine-tuning LLMs on these preference datasets
reduces the hallucination rate by an average of 96% across five language pairs,
while preserving overall translation quality. In a zero-shot setting our
approach reduces hallucinations by 89% on an average across three unseen target
languages.
