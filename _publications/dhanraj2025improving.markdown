---
layout: publication
title: 'Improving Rule-based Reasoning In Llms Using Neurosymbolic Representations'
authors: Varun Dhanraj, Chris Eliasmith
conference: "Arxiv"
year: 2025
bibkey: dhanraj2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01657"}
  - {name: "Code", url: "https://github.com/vdhanraj/Neurosymbolic-LLM"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) continue to face challenges in reliably solving reasoning tasks, particularly those that require precise rule following, as often found in mathematical reasoning. This paper introduces a novel neurosymbolic method that improves LLM reasoning by encoding hidden states into neurosymbolic vectors, enabling problem-solving within a neurosymbolic vector space. The results are decoded and merged with the original hidden state, significantly boosting the model's performance on numerical reasoning tasks. By offloading computation through neurosymbolic representations, this method enhances efficiency, reliability, and interpretability. Experimental results demonstrate an average of 88.6% lower cross-entropy loss and 15.4 times more problems correctly solved on a suite of mathematical reasoning tasks compared to chain-of-thought prompting and supervised fine-tuning (LoRA), without degrading performance on other tasks. We make our code available at: https://github.com/vdhanraj/Neurosymbolic-LLM.
