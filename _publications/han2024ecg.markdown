---
layout: publication
title: 'Ecg-byte: A Tokenizer For End-to-end Generative Electrocardiogram Language Modeling'
authors: William Han, Chaojing Duan, Michael A. Rosenberg, Emerson Liu, Ding Zhao
conference: "Arxiv"
year: 2024
bibkey: han2024ecg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14373"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Interpretability and Explainability', 'Prompting']
---
Large Language Models (LLMs) have shown remarkable adaptability across
domains beyond text, specifically electrocardiograms (ECGs). More specifically,
there is a growing body of work exploring the task of generating text from a
multi-channeled ECG and corresponding textual prompt. Current approaches
typically involve pretraining an ECG-specific encoder with a self-supervised
learning (SSL) objective and using the features output by the pretrained
encoder to finetune a LLM for natural language generation (NLG). However, these
methods are limited by 1) inefficiency from two-stage training and 2)
interpretability challenges with encoder-generated features. To address these
limitations, we introduce ECG-Byte, an adapted byte pair encoding (BPE)
tokenizer pipeline for autoregressive language modeling of ECGs. This approach
compresses and encodes ECG signals into tokens, enabling end-to-end LLM
training by combining ECG and text tokens directly, while being much more
interpretable since the ECG tokens can be directly mapped back to the original
signal. Using ECG-Byte, we achieve competitive performance in NLG tasks in only
half the time and ~48% of the data required by two-stage approaches.
