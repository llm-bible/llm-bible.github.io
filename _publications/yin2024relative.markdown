---
layout: publication
title: 'Relative Preference Optimization: Enhancing LLM Alignment Through Contrasting Responses Across Identical And Diverse Prompts'
authors: Yueqin Yin, Zhendong Wang, Yi Gu, Hai Huang, Weizhu Chen, Mingyuan Zhou
conference: "Arxiv"
year: 2024
bibkey: yin2024relative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10958"}
  - {name: "Code", url: "https://github.com/yinyueqin/relative-preference-optimization"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting']
---
In the field of large language models (LLMs), aligning models with the
diverse preferences of users is a critical challenge. Direct Preference
Optimization (DPO) has played a key role in this area. It works by using pairs
of preferences derived from the same prompts, and it functions without needing
an additional reward model. However, DPO does not fully reflect the complex
nature of human learning, which often involves understanding contrasting
responses to not only identical but also similar questions. To overcome this
shortfall, we propose Relative Preference Optimization (RPO). RPO is designed
to discern between more and less preferred responses derived from both
identical and related prompts. It introduces a contrastive weighting mechanism,
enabling the tuning of LLMs using a broader range of preference data, including
both paired and unpaired sets. This approach expands the learning capabilities
of the model, allowing it to leverage insights from a more varied set of
prompts. Through empirical tests, including dialogue and summarization tasks,
and evaluations using the AlpacaEval2.0 leaderboard, RPO has demonstrated a
superior ability to align LLMs with user preferences and to improve their
adaptability during the training process. Our code can be viewed at
https://github.com/yinyueqin/relative-preference-optimization
