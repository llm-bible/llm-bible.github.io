---
layout: publication
title: LeTI Learning to Generate from Textual Interactions
authors: Wang Xingyao, Peng Hao, Jabbarvand Reyhaneh, Ji Heng
conference: "Arxiv"
year: 2023
bibkey: wang2023leti
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10314"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Fine-tuning pre-trained language models (LMs) is essential for enhancing their capabilities. Existing techniques commonly fine-tune on input-output pairs (e.g. instruction tuning) or with numerical rewards that gauge the output quality (e.g. RLHF). We explore LMs potential to learn from textual interactions (LETI) that not only check their correctness with binary labels but also pinpoint and explain errors in their outputs through textual feedback. Our focus is the code generation task where the model produces code based on natural language instructions. This setting invites a natural and scalable way to acquire textual feedback the error messages and stack traces from code execution using a Python interpreter. LETI iteratively fine-tunes the model using the LM objective on a concatenation of natural language instructions LM-generated programs and textual feedback. Prepended to this fine-tuning text a binary reward token is used to differentiate correct and buggy solutions. LETI requires no ground-truth outputs for training and even outperforms a fine-tuned baseline that does. LETI not only improves the performance of LMs on a code generation dataset MBPP but also generalizes to other datasets. Trained on MBPP it achieves comparable or better performance than the base LMs on unseen problems in HumanEval. Furthermore compared to binary feedback we observe that textual feedback leads to improved generation quality and sample efficiency achieving the same performance with fewer than half of the gradient steps. LETI is equally applicable in natural language tasks when they can be formulated as code generation which we empirically verified on event argument extraction.
