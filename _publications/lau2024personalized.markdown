---
layout: publication
title: 'Personalized Adaptation Via In-context Preference Learning'
authors: Allison Lau, Younwoo Choi, Vahid Balazadeh, Keertana Chidambaram, Vasilis Syrgkanis, Rahul G. Krishnan
conference: "Arxiv"
year: 2024
bibkey: lau2024personalized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14001'}
tags: ['Agentic', 'Transformer', 'RAG', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Reinforcement Learning from Human Feedback (RLHF) is widely used to align
Language Models (LMs) with human preferences. However, existing approaches
often neglect individual user preferences, leading to suboptimal
personalization. We present the Preference Pretrained Transformer (PPT), a
novel approach for adaptive personalization using online user feedback. PPT
leverages the in-context learning capabilities of transformers to dynamically
adapt to individual preferences. Our approach consists of two phases: (1) an
offline phase where we train a single policy model using a history-dependent
loss function, and (2) an online phase where the model adapts to user
preferences through in-context learning. We demonstrate PPT's effectiveness in
a contextual bandit setting, showing that it achieves personalized adaptation
superior to existing methods while significantly reducing the computational
costs. Our results suggest the potential of in-context learning for scalable
and efficient personalization in large language models.
