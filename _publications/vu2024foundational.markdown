---
layout: publication
title: Foundational Autoraters Taming Large Language Models For Better Automatic Evaluation
authors: Vu Tu, Krishna Kalpesh, Alzubi Salaheddin, Tar Chris, Faruqui Manaal, Sung Yun-hsuan
conference: "Arxiv"
year: 2024
bibkey: vu2024foundational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10817"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
As large language models (LLMs) advance it becomes more challenging to reliably evaluate their output due to the high costs of human evaluation. To make progress towards better LLM autoraters we introduce FLAMe a family of Foundational Large Autorater Models. FLAMe is trained on our large and diverse collection of 100+ quality assessment tasks comprising 5M+ human judgments curated and standardized using publicly released human evaluations from previous research. FLAMe significantly improves generalization to a wide variety of held45;out tasks outperforming LLMs trained on proprietary data like GPT45;4 and Claude45;3 on many tasks. We show that FLAMe can also serve as a powerful starting point for further downstream fine45;tuning using reward modeling evaluation as a case study (FLAMe45;RM). Notably on RewardBench our FLAMe45;RM45;24B model (with an accuracy of 87.837;) is the top45;performing generative model trained exclusively on permissively licensed data outperforming both GPT45;445;0125 (85.937;) and GPT45;4o (84.737;). Additionally we explore a more computationally efficient approach using a novel tail45;patch fine45;tuning strategy to optimize our FLAMe multitask mixture for reward modeling evaluation (FLAMe45;Opt45;RM) offering competitive RewardBench performance while requiring approximately 25x less training datapoints. Overall our FLAMe variants outperform all popular proprietary LLM45;as45;a45;Judge models we consider across 8 out of 12 autorater evaluation benchmarks encompassing 53 quality assessment tasks including RewardBench and LLM45;AggreFact. Finally our analysis reveals that FLAMe is significantly less biased than these LLM45;as45;a45;Judge models on the CoBBLEr autorater bias benchmark while effectively identifying high45;quality responses for code generation.
