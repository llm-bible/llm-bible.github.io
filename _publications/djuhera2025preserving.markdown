---
layout: publication
title: 'Safemerge: Preserving Safety Alignment In Fine-tuned Large Language Models Via Selective Layer-wise Model Merging'
authors: Aladin Djuhera, Swanand Ravindra Kadhe, Farhan Ahmed, Syed Zawad, Holger Boche
conference: "ICLR 2025 Workshop on Building Trust in Language Models and Applications"
year: 2025
bibkey: djuhera2025preserving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17239'}
tags: ['Training Techniques', 'Tools', 'Merging', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) on downstream tasks can
inadvertently erode their safety alignment, even for benign fine-tuning
datasets. We address this challenge by proposing SafeMERGE, a post-fine-tuning
framework that preserves safety while maintaining task utility. It achieves
this by selectively merging fine-tuned and safety-aligned model layers only
when those deviate from safe behavior, measured by a cosine similarity
criterion. We evaluate SafeMERGE against other fine-tuning- and
post-fine-tuning-stage approaches for Llama-2-7B-Chat and Qwen-2-7B-Instruct
models on GSM8K and PubMedQA tasks while exploring different merging
strategies. We find that SafeMERGE consistently reduces harmful outputs
compared to other baselines without significantly sacrificing performance,
sometimes even enhancing it. The results suggest that our selective,
subspace-guided, and per-layer merging method provides an effective safeguard
against the inadvertent loss of safety in fine-tuned LLMs while outperforming
simpler post-fine-tuning-stage defenses.
