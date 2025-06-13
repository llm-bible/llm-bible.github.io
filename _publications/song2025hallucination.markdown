---
layout: publication
title: 'The Hallucination Tax Of Reinforcement Finetuning'
authors: Linxin Song, Taiwei Shi, Jieyu Zhao
conference: "Arxiv"
year: 2025
bibkey: song2025hallucination
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13988'}
tags: ['RAG', 'Applications', 'Training Techniques']
---
Reinforcement finetuning (RFT) has become a standard approach for enhancing the reasoning capabilities of large language models (LLMs). However, its impact on model trustworthiness remains underexplored. In this work, we identify and systematically study a critical side effect of RFT, which we term the hallucination tax: a degradation in refusal behavior causing models to produce hallucinated answers to unanswerable questions confidently. To investigate this, we introduce SUM (Synthetic Unanswerable Math), a high-quality dataset of unanswerable math problems designed to probe models' ability to recognize an unanswerable question by reasoning from the insufficient or ambiguous information. Our results show that standard RFT training could reduce model refusal rates by more than 80%, which significantly increases model's tendency to hallucinate. We further demonstrate that incorporating just 10% SUM during RFT substantially restores appropriate refusal behavior, with minimal accuracy trade-offs on solvable tasks. Crucially, this approach enables LLMs to leverage inference-time compute to reason about their own uncertainty and knowledge boundaries, improving generalization not only to out-of-domain math problems but also to factual question answering tasks.
