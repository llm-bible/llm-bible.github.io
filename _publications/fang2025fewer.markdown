---
layout: publication
title: 'Fewer Hallucinations, More Verification: A Three-stage Llm-based Framework For ASR Error Correction'
authors: Yangui Fang, Baixu Cheng, Jing Peng, Xu Li, Yu Xi, Chengwei Zhang, Guohui Zhong
conference: "Arxiv"
year: 2025
bibkey: fang2025fewer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24347'}
tags: ['INTERSPEECH', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Automatic Speech Recognition (ASR) error correction aims to correct recognition errors while preserving accurate text. Although traditional approaches demonstrate moderate effectiveness, LLMs offer a paradigm that eliminates the need for training and labeled data. However, directly using LLMs will encounter hallucinations problem, which may lead to the modification of the correct text. To address this problem, we propose the Reliable LLM Correction Framework (RLLM-CF), which consists of three stages: (1) error pre-detection, (2) chain-of-thought sub-tasks iterative correction, and (3) reasoning process verification. The advantage of our method is that it does not require additional information or fine-tuning of the model, and ensures the correctness of the LLM correction under multi-pass programming. Experiments on AISHELL-1, AISHELL-2, and Librispeech show that the GPT-4o model enhanced by our framework achieves 21%, 11%, 9%, and 11.4% relative reductions in CER/WER.
