---
layout: publication
title: 'How Likely Do Llms With Cot Mimic Human Reasoning?'
authors: Guangsheng Bao, Hongbo Zhang, Cunxiang Wang, Linyi Yang, Yue Zhang
conference: "Arxiv"
year: 2024
bibkey: bao2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16048"}
tags: ['Fine-Tuning', 'Agentic', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Chain-of-thought emerges as a promising technique for eliciting reasoning
capabilities from Large Language Models (LLMs). However, it does not always
improve task performance or accurately represent reasoning processes, leaving
unresolved questions about its usage. In this paper, we diagnose the underlying
mechanism by comparing the reasoning process of LLMs with humans, using causal
analysis to understand the relationships between the problem instruction,
reasoning, and the answer in LLMs. Our empirical study reveals that LLMs often
deviate from the ideal causal chain, resulting in spurious correlations and
potential consistency errors (inconsistent reasoning and answers). We also
examine various factors influencing the causal structure, finding that
in-context learning with examples strengthens it, while post-training
techniques like supervised fine-tuning and reinforcement learning on human
feedback weaken it. To our surprise, the causal structure cannot be
strengthened by enlarging the model size only, urging research on new
techniques. We hope that this preliminary study will shed light on
understanding and improving the reasoning process in LLM.
