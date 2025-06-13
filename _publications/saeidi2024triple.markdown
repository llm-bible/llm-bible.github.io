---
layout: publication
title: 'Triple Preference Optimization: Achieving Better Alignment Using A Single Step Optimization'
authors: Amir Saeidi, Shivanshu Verma, Aswin Rrv, Kashif Rasul, Chitta Baral
conference: "Arxiv"
year: 2024
bibkey: saeidi2024triple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.16681'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Reinforcement Learning with Human Feedback (RLHF) enhances the alignment of
Large Language Models (LLMs). However, its limitations have led to the
development of Direct Preference Optimization (DPO), an RL-free approach
designed to overcome these shortcomings. While studies have shown that DPO
improves instruction-following capabilities, it negatively impacts the
reasoning ability of LLMs. Additionally, DPO is highly sensitive to judgment
noise in preference datasets and the size of the training set. Although several
modifications to DPO have been proposed, they still fail to fully resolve these
issues. To address these limitations, we propose Triple Preference Optimization
(TPO), a new preference learning method designed to enhance both reasoning and
instruction-following abilities through one-step optimization. We compare TPO
against DPO and its recent variants using state-of-the-art training setups,
including both base and instruction-tuned models such as Mistral and Llama 3.
Our evaluation covers a comprehensive range of chat-based and reasoning
benchmarks. The results demonstrate that TPO achieves significant improvements
over existing methods without substantially increasing response length across
different dataset sizes. Specifically, TPO outperforms DPO and SimPO by up to
7.0% and 7.3% points on Arena-Hard, 12.2% and 13.3% points on MixEval-Hard,
10.4% and 10.1% points on MMLU-Pro, and 19.0% and 19.2% points on GSM8K,
respectively. Furthermore, TPO achieves these improvements while requiring less
data than DPO.
