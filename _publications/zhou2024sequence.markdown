---
layout: publication
title: Sequence To Sequence Reward Modeling: Improving RLHF By Language Feedback
authors: Zhou Jiayi, Ji Jiaming, Dai Juntao, Yang Yaodong
conference: "Arxiv"
year: 2024
bibkey: zhou2024sequence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00162"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Aligning the behavior of Large language models (LLMs) with human intentions and values remains a critical challenge. Reinforcement learning from human feedback (RLHF) aligns LLMs by training a reward model (RM) on human preferences and fine-tuning the LLMs to maximize RM feedback. Despite its effectiveness and popularity RLHF is prone to biased local optimization. It means RM fails to provide feedback that accurately aligns with human preference causing LLMs to explore unexpected generalizations and failing to achieve alignment objectives. To mitigate this issue we propose a novel (textit)sequence-to-sequence (seq2seq) reward modeling method. Its key insight is that learning from language feedback rather than scalar feedback improves RLHF without additional annotations. We replaced the reward modeling target from binary maximum likelihood estimation (MLE) with sequence MLE. This method enables richer and fine-grained language feedback without additional annotations models or training stages. Our experiments demonstrated its effectiveness specifically reducing the refusal-to-response paradigm in single-turn safety dialogues and the long-response bias in text summarization tasks. We provide further analysis that seq2seq RM improves RLHF performance across 2B and 7B LLMs on 3 NLP tasks achieving an average win rate of 76.937;. We further show that seq2seq RM can still improve the performance of RLHF under out-of-distribution prompts.
