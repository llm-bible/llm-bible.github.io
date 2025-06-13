---
layout: publication
title: 'Reinforcement Learning From User Feedback'
authors: Eric Han, Jun Chen, Karthik Abinav Sankararaman, Xiaoliang Peng, Tengyu Xu, Eryk Helenowski, Kaiyan Peng, Mrinal Kumar, Sinong Wang, Han Fang, Arya Talebzadeh
conference: "Arxiv"
year: 2025
bibkey: han2025reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14946"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
As large language models (LLMs) are increasingly deployed in diverse user facing applications, aligning them with real user preferences becomes essential. Existing methods like Reinforcement Learning from Human Feedback (RLHF) rely on expert annotators trained on manually defined guidelines, whose judgments may not reflect the priorities of everyday users. We introduce Reinforcement Learning from User Feedback (RLUF), a framework for aligning LLMs directly to implicit signals from users in production. RLUF addresses key challenges of user feedback: user feedback is often binary (e.g., emoji reactions), sparse, and occasionally adversarial. We train a reward model, P[Love], to predict the likelihood that an LLM response will receive a Love Reaction, a lightweight form of positive user feedback, and integrate P[Love] into a multi-objective policy optimization framework alongside helpfulness and safety objectives. In large-scale experiments, we show that P[Love] is predictive of increased positive feedback and serves as a reliable offline evaluator of future user behavior. Policy optimization using P[Love] significantly raises observed positive-feedback rates, including a 28% increase in Love Reactions during live A/B tests. However, optimizing for positive reactions introduces reward hacking challenges, requiring careful balancing of objectives. By directly leveraging implicit signals from users, RLUF offers a path to aligning LLMs with real-world user preferences at scale.
