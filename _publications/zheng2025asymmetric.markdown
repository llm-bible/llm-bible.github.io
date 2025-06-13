---
layout: publication
title: 'Asymmetric Conflict And Synergy In Post-training For Llm-based Multilingual Machine Translation'
authors: Tong Zheng, Yan Wen, Huiwen Bao, Junfeng Guo, Heng Huang
conference: "Arxiv"
year: 2025
bibkey: zheng2025asymmetric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11223"}
tags: ['Fine-Tuning', 'Pre-Training', 'Applications', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
The emergence of Large Language Models (LLMs) has advanced the multilingual
machine translation (MMT), yet the Curse of Multilinguality (CoM) remains a
major challenge. Existing work in LLM-based MMT typically mitigates this issue
via scaling up training and computation budget, which raises a critical
question: Is scaling up the training and computation budget truly necessary for
high-quality MMT, or can a deeper understanding of CoM provide a more efficient
solution? To explore this problem, we analyze the linguistic conflicts and
synergy, the underlying mechanism of CoM during post-training phase. We
identify an asymmetric phenomenon in linguistic conflicts and synergy: the
dominance of conflicts and synergy varies in different translation directions,
leading to sub-optimal adaptation in existing post-training methods. We further
find that a significant bottleneck in MMT appears to lie in post-training
rather than multilingual pre-training, suggesting the need for more effective
adaptation strategies. Building on these new insights, we propose a
direction-aware training approach, combined with group-wise model merging, to
address asymmetry in linguistic conflicts and synergy explicitly. Leveraging
this strategy, our method fine-tunes X-ALMA-13B-Pretrain-trained only with
multilingual pre-training-achieving comparable performance to XALMA-13B (only
SFT) while using only 20B pretraining tokens and 17B parameters-5.5x fewer
pretraining-tokens and 1.7x fewer model size-with just 0.85 COMET drop on
Flores-200 testsets of 50 languages.
