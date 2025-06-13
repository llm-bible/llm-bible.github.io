---
layout: publication
title: 'Language-specific Neurons Do Not Facilitate Cross-lingual Transfer'
authors: Soumen Kumar Mondal, Sayambhu Sen, Abhishek Singhania, Preethi Jyothi
conference: "Arxiv"
year: 2025
bibkey: mondal2025language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17456'}
tags: ['RAG', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Multilingual large language models (LLMs) aim towards robust natural language
understanding across diverse languages, yet their performance significantly
degrades on low-resource languages. This work explores whether existing
techniques to identify language-specific neurons can be leveraged to enhance
cross-lingual task performance of lowresource languages. We conduct detailed
experiments covering existing language-specific neuron identification
techniques (such as Language Activation Probability Entropy and activation
probability-based thresholding) and neuron-specific LoRA fine-tuning with
models like Llama 3.1 and Mistral Nemo. We find that such neuron-specific
interventions are insufficient to yield cross-lingual improvements on
downstream tasks (XNLI, XQuAD) in lowresource languages. This study highlights
the challenges in achieving cross-lingual generalization and provides critical
insights for multilingual LLMs.
