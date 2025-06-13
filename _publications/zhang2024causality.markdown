---
layout: publication
title: 'Causality-enhanced Behavior Sequence Modeling In Llms For Personalized Recommendation'
authors: Yang Zhang, Juntao You, Yimeng Bai, Jizhi Zhang, Keqin Bao, Wenjie Wang, Tat-seng Chua
conference: "Arxiv"
year: 2024
bibkey: zhang2024causality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22809"}
  - {name: "Code", url: "https://github.com/itsmeyjt/CFT"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'RecSys', 'Has Code', 'Pretraining Methods']
---
Recent advancements in recommender systems have focused on leveraging Large
Language Models (LLMs) to improve user preference modeling, yielding promising
outcomes. However, current LLM-based approaches struggle to fully leverage user
behavior sequences, resulting in suboptimal preference modeling for
personalized recommendations. In this study, we propose a novel Counterfactual
Fine-Tuning (CFT) method to address this issue by explicitly emphasizing the
role of behavior sequences when generating recommendations. Specifically, we
employ counterfactual reasoning to identify the causal effects of behavior
sequences on model output and introduce a task that directly fits the
ground-truth labels based on these effects, achieving the goal of explicit
emphasis. Additionally, we develop a token-level weighting mechanism to adjust
the emphasis strength for different item tokens, reflecting the diminishing
influence of behavior sequences from earlier to later tokens during predicting
an item. Extensive experiments on real-world datasets demonstrate that CFT
effectively improves behavior sequence modeling. Our codes are available at
https://github.com/itsmeyjt/CFT.
