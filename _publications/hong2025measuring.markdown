---
layout: publication
title: 'Measuring Sycophancy Of Language Models In Multi-turn Dialogues'
authors: Jiseung Hong, Grace Byun, Seungone Kim, Kai Shu
conference: "Arxiv"
year: 2025
bibkey: hong2025measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23840"}
  - {name: "Code", url: "https://github.com/JiseungHong/SYCON-Bench"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning', 'Has Code', 'Scaling Laws', 'Prompting']
---
Large Language Models (LLMs) are expected to provide helpful and harmless responses, yet they often exhibit sycophancy--conforming to user beliefs regardless of factual accuracy or ethical soundness. Prior research on sycophancy has primarily focused on single-turn factual correctness, overlooking the dynamics of real-world interactions. In this work, we introduce SYCON Bench, a novel benchmark for evaluating sycophantic behavior in multi-turn, free-form conversational settings. Our benchmark measures how quickly a model conforms to the user (Turn of Flip) and how frequently it shifts its stance under sustained user pressure (Number of Flip). Applying SYCON Bench to 17 LLMs across three real-world scenarios, we find that sycophancy remains a prevalent failure mode. Our analysis shows that alignment tuning amplifies sycophantic behavior, whereas model scaling and reasoning optimization strengthen the model's ability to resist undesirable user views. Reasoning models generally outperform instruction-tuned models but often fail when they over-index on logical exposition instead of directly addressing the user's underlying beliefs. Finally, we evaluate four additional prompting strategies and demonstrate that adopting a third-person perspective reduces sycophancy by up to 63.8% in debate scenario. We release our code and data at https://github.com/JiseungHong/SYCON-Bench.
