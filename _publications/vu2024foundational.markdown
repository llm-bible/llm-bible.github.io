---
layout: publication
title: Foundational Autoraters Taming Large Language Models For Better Automatic Evaluation
authors: Vu Tu, Krishna Kalpesh, Alzubi Salaheddin, Tar Chris, Faruqui Manaal, Sung Yun-hsuan
conference: "Arxiv"
year: 2024
bibkey: vu2024foundational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10817"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
As large language models (LLMs) advance it becomes more challenging to reliably evaluate their output due to the high costs of human evaluation. To make progress towards better LLM autoraters we introduce FLAMe a family of Foundational Large Autorater Models. FLAMe is trained on our large and diverse collection of 100+ quality assessment tasks comprising 5M+ human judgments curated and standardized using publicly released human evaluations from previous research. FLAMe significantly improves generalization to a wide variety of held-out tasks outperforming LLMs trained on proprietary data like GPT-4 and Claude-3 on many tasks. We show that FLAMe can also serve as a powerful starting point for further downstream fine-tuning using reward modeling evaluation as a case study (FLAMe-RM). Notably on RewardBench our FLAMe-RM-24B model (with an accuracy of 87.837;) is the top-performing generative model trained exclusively on permissively licensed data outperforming both GPT-4-0125 (85.937;) and GPT-4o (84.737;). Additionally we explore a more computationally efficient approach using a novel tail-patch fine-tuning strategy to optimize our FLAMe multitask mixture for reward modeling evaluation (FLAMe-Opt-RM) offering competitive RewardBench performance while requiring approximately 25x less training datapoints. Overall our FLAMe variants outperform all popular proprietary LLM-as-a-Judge models we consider across 8 out of 12 autorater evaluation benchmarks encompassing 53 quality assessment tasks including RewardBench and LLM-AggreFact. Finally our analysis reveals that FLAMe is significantly less biased than these LLM-as-a-Judge models on the CoBBLEr autorater bias benchmark while effectively identifying high-quality responses for code generation.
