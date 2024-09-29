---
layout: publication
title: Sequence To Sequence Reward Modeling Improving RLHF By Language Feedback
authors: Zhou Jiayi, Ji Jiaming, Dai Juntao, Yang Yaodong
conference: "Arxiv"
year: 2024
bibkey: zhou2024sequence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00162"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Ethics And Bias', 'Prompting', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Aligning the behavior of Large language models (LLMs) with human intentions and values remains a critical challenge. Reinforcement learning from human feedback (RLHF) aligns LLMs by training a reward model (RM) on human preferences and fine45;tuning the LLMs to maximize RM feedback. Despite its effectiveness and popularity RLHF is prone to biased local optimization. It means RM fails to provide feedback that accurately aligns with human preference causing LLMs to explore unexpected generalizations and failing to achieve alignment objectives. To mitigate this issue we propose a novel textit123;sequence45;to45;sequence (seq2seq) reward modeling125; method. Its key insight is that learning from language feedback rather than scalar feedback improves RLHF without additional annotations. We replaced the reward modeling target from binary maximum likelihood estimation (MLE) with sequence MLE. This method enables richer and fine45;grained language feedback without additional annotations models or training stages. Our experiments demonstrated its effectiveness specifically reducing the refusal45;to45;response paradigm in single45;turn safety dialogues and the long45;response bias in text summarization tasks. We provide further analysis that seq2seq RM improves RLHF performance across 2B and 7B LLMs on 3 NLP tasks achieving an average win rate of 76.937;. We further show that seq2seq RM can still improve the performance of RLHF under out45;of45;distribution prompts.
