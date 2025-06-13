---
layout: publication
title: 'Transformllm: Adapting Large Language Models Via Llm-transformed Reading Comprehension Text'
authors: Iftach Arbel, Yehonathan Refael, Ofir Lindenbaum
conference: "Arxiv"
year: 2024
bibkey: arbel2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21479"}
tags: ['Fine-Tuning', 'Pre-Training', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have shown promise in highly-specialized
domains, however challenges are still present in aspects of accuracy and costs.
These limitations restrict the usage of existing models in domain-specific
tasks. While fine-tuning pre-trained models have shown promising results, this
process can be computationally expensive and require massive datasets of the
specialized application in hand. In this work, we bridge that gap. We have
developed Phi-2-Legal and Mistral-Legal-7B, which are language models
specifically designed for legal applications. These models are based on Phi-2
and Mistral-7B-v0.1, and have gone through continued pre-training with over 500
million tokens of legal texts. Our innovative approach significantly improves
capabilities in legal tasks by using Large Language Models (LLMs) to convert
raw training data into reading comprehension text. Our legal LLMs have
demonstrated superior performance in legal benchmarks, even outperforming
models trained on much larger datasets with more resources. This work
emphasizes the effectiveness of continued pre-training on domain-specific
texts, while using affordable LLMs for data conversion, which gives these
models domain expertise while retaining general language understanding
capabilities. While this work uses the legal domain as a test case, our method
can be scaled and applied to any pre-training dataset, resulting in significant
improvements across different tasks. These findings underscore the potential of
domain-adaptive pre-training and reading comprehension for the development of
highly effective domain-specific language models.
