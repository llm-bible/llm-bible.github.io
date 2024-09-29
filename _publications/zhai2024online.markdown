---
layout: publication
title: Online Self45;preferring Language Models
authors: Zhai Yuanzhao, Zhang Zhuo, Xu Kele, Peng Hanyang, Yu Yue, Feng Dawei, Yang Cheng, Ding Bo, Wang Huaimin
conference: "Arxiv"
year: 2024
bibkey: zhai2024online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14103"}
tags: ['Agentic', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Aligning with human preference datasets has been critical to the success of large language models (LLMs). Reinforcement learning from human feedback (RLHF) employs a costly reward model to provide feedback for on45;policy sampling responses. Recently offline methods that directly fit responses with binary preferences in the dataset have emerged as alternatives. However existing methods do not explicitly model preference strength information which is crucial for distinguishing different response pairs. To overcome this limitation we propose Online Self45;Preferring (OSP) language models to learn from self45;generated response pairs and self45;judged preference strengths. For each prompt and corresponding self45;generated responses we introduce a ranked pairing method to construct multiple response pairs with preference strength information. We then propose the soft45;preference cross45;entropy loss to leverage such information. Empirically we demonstrate that leveraging preference strength is crucial for avoiding overfitting and enhancing alignment performance. OSP achieves state45;of45;the45;art alignment performance across various metrics in two widely used human preference datasets. OSP is parameter45;efficient and more robust than the dominant online method RLHF when limited offline data are available and generalizing to out45;of45;domain tasks. Moreover OSP language models established by LLMs with proficiency in self45;preferring can efficiently self45;improve without external supervision.
