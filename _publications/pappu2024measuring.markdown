---
layout: publication
title: Measuring Memorization In RLHF For Code Completion
authors: Pappu Aneesh, Porter Billy, Shumailov Ilia, Hayes Jamie
conference: "Arxiv"
year: 2024
bibkey: pappu2024measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11715"}
tags: ['Agentic', 'Applications', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement learning with human feedback (RLHF) has become the dominant method to align large models to user preferences. Unlike fine45;tuning for which there are many studies regarding training data memorization it is not clear how memorization is affected by or introduced in the RLHF alignment process. Understanding this relationship is important as real user data may be collected and used to align large models; if user data is memorized during RLHF and later regurgitated this could raise privacy concerns. In this work we analyze how training data memorization can surface and propagate through each phase of RLHF. We focus our study on code completion models as code completion is one of the most popular use cases for large language models. We find that RLHF significantly decreases the chance that data used for reward modeling and reinforcement learning is memorized in comparison to aligning via directly fine45;tuning on this data but that examples already memorized during the fine45;tuning stage of RLHF will in the majority of cases remain memorized after RLHF.
