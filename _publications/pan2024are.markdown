---
layout: publication
title: 'Are Llms Good Zero-shot Fallacy Classifiers?'
authors: Fengjun Pan, Xiaobao Wu, Zongrui Li, Anh Tuan Luu
conference: "Arxiv"
year: 2024
bibkey: pan2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15050"}
  - {name: "Code", url: "https://github.com/panFJCharlotte98/Fallacy_Detection"}
tags: ['Ethics and Bias', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting']
---
Fallacies are defective arguments with faulty reasoning. Detecting and
classifying them is a crucial NLP task to prevent misinformation, manipulative
claims, and biased decisions. However, existing fallacy classifiers are limited
by the requirement for sufficient labeled data for training, which hinders
their out-of-distribution (OOD) generalization abilities. In this paper, we
focus on leveraging Large Language Models (LLMs) for zero-shot fallacy
classification. To elicit fallacy-related knowledge and reasoning abilities of
LLMs, we propose diverse single-round and multi-round prompting schemes,
applying different task-specific instructions such as extraction,
summarization, and Chain-of-Thought reasoning. With comprehensive experiments
on benchmark datasets, we suggest that LLMs could be potential zero-shot
fallacy classifiers. In general, LLMs under single-round prompting schemes have
achieved acceptable zero-shot performances compared to the best full-shot
baselines and can outperform them in all OOD inference scenarios and some
open-domain tasks. Our novel multi-round prompting schemes can effectively
bring about more improvements, especially for small LLMs. Our analysis further
underlines the future research on zero-shot fallacy classification. Codes and
data are available at: https://github.com/panFJCharlotte98/Fallacy_Detection.
